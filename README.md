# 关于Sentry

Sentry平台，从简单的说是一个在线日志收集平台。从复杂说的可以帮我们处理从bug发生、定位、源码追溯、bug管理、修复、追踪，甚至是关联git和ci等一系列复杂流程。

使用Sentry是为了帮助我们从繁琐、复杂的日志收集工作中解放出来，提升开发效率。

同时Sentry几乎支持全平台全语言，也提供http接口方便各类框架接入，保证了扩展性和适用性。

如果希望更深入了解Sentry，可以直接访问Sentry官网：
https://sentry.io/welcome/

Sentry是一个开源平台，可以通过docker部署Sentry到本地，或者到自己的公网服务器。

如果不想自己部署，也可以直接使用在线版的Sentry，但是这个针对不同使用量收费不同，也有一些限制。自己部署则完全免费也无功能限制。


# 关于JQSentry

JQSentry基于Sentry的HTTP接口封装而来，目前一共有3个主要功能

* 日志 & 异常 收集

* minidump 收集

* performance & trace 收集

为了保证使用足够轻量级，方便嵌入到各种系统中。JQSentry被完整封装在一个cpp和一个h文件中，并且只依赖Qt库。

理论上可以部署到 Qt5 & C++11 的所有环境中。

若你遇到问题、有了更好的建议或者想要一些新功能，都可以直接在GitHub上提交Issues：https://github.com/188080501/JQSentry/issues

