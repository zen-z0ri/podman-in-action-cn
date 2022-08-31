---
description: 感谢
---

# 前言

感谢您购买_**《Podman实战》**_。为了更好地理解这本书，您应该对进程是如何在Linux中运行的有一些理解。使用命令行也是必要的。关于Docker的知识对理解本书会有帮助，但不是必需的。

当我二十年前刚开始接触容器技术的时候，我们甚至不把它们叫做容器（containers），我们称其沙箱（sandboxes）。早在2008年，我创建了一个叫做SELinux sandbox的工具，它使用像SELinux、挂载命名空间（the mount namespace）和cgroups等安全工具来控制桌面应用访问home目录。当2013年Docker爆炸式的增长时，我的任务是领导一个 Red Hat 的工程师团队承接上游的Docker项目。一开始接触Docker，我就认识到这是怎样一项突破性的技术，但我认为它的设计存在一些问题。我不希望以root权限去运行一个中心化的守护进程。通过利用更多的操作系统核心概念，存在更好的方式去运行容器，这导致了Podman和其他容器工具的诞生。

当设计Podman的时候，我们意识到其CLI和API必须与Docker中的相匹配，并且利用我们多年使用容器化负载的心得来扩展技术。凭借我40年的计算机安全背景，我想要利用操作系统提供的一切去保障容器的安全，在本书中你会学到很多相关内容。

通读这本书你会学到Podman是怎样与核心操作系统（CoreOS）交互的，以利用操作系统的所有相关特性来隔离容器化应用。这种隔离性是从安全和资源限制的角度出发的，以确保应用运行在一个专有系统中。

我相信这本书对构建容器化应用程序的开发人员以及学习如何运行这些容器化工具的系统管理员很有用，而且对希望了解容器的工程师也很有帮助。

如果您对 Docker 有坚实的了解，您可以略读其中的一些章节，进入涵盖 Podman 的一些关键区别的部分。

再次感谢您的关注和购买 MEAP！

如果您有任何问题、意见或者建议，请分享到[livebook 论坛](https://livebook.manning.com/book/podman-the-next-generation-of-container-engines/welcome/v-6/)

—Dan Walsh

{% hint style="success" %}
[Copyright 2022 Manning Publications](https://livebook.manning.com/book/podman-in-action/copyright-2022-manning-publications/v-6) [welcome](https://livebook.manning.com/book/podman-in-action/welcome/v-6) [brief contents](https://livebook.manning.com/book/podman-in-action/brief-contents/v-6)

1. [Podman: 下一代容器技术](broken-reference)  _Podman: next generation container engine_
2. 命令行  _Command line_
3. 卷  Volumns
4. [Pods](https://livebook.manning.com/book/podman-in-action/chapter-4/v-5)
5. 客制化和配置文件  [Customization and configuration files](https://livebook.manning.com/book/podman-in-action/chapter-5/v-5)
6. 非Root容器  [Rootless containers](https://livebook.manning.com/book/podman-in-action/chapter-6/v-5)
7. 系统集成  [Integration with System](https://livebook.manning.com/book/podman-in-action/chapter-7/v-5)
8. 与Kubernetes交互  [Working with Kubernetes](https://livebook.manning.com/book/podman-in-action/chapter-8/v-5)
{% endhint %}

{% content-ref url="broken-reference" %}
[Broken link](broken-reference)
{% endcontent-ref %}

