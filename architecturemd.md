# 进程内微服务架构

我们用一张图开始这章的内容。

![进程内微服务架构](inprocess-microservices.png)

在上图中，`management node`是一个独立的进程，是所有微服务的container，用于管理微服务的生命周期，提供统一的服务监控和HA（高可靠）等功能。

