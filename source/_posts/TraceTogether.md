---
title: 新冠病毒追踪接触人，为什么不会侵犯个人隐私问题？
tags:
  - 产品
abbrlink: f41e9f4d
date: 2020-05-15 23:56:41
---
新加坡政府前段时间发布了个 App —— TraceTogether，用来追踪新冠病毒患者接触过的人。在刚听到这个时，还是会有一些抵触的，感觉可能会在无形之中被收集了个人数据（什么时候，到过哪里）。今天无意中看到个讲解，通过蓝牙和密码学的方法，完全不会有个人数据泄露的问题。

追踪流程如下：

1. 小明和小红都下载了 App，并且打开了蓝牙，同时在地铁一节车厢里待了5分钟以上。
2. 每隔5分钟，小明会生成一个加密后的乱码 `zs8dA`，储存在本地，并通过蓝牙发给小红，小红收到后，会将这个乱码储存在本地。同时小红也会做同样的操作。
3. 第二天，小明确诊了，通过他在过去14天里发出的所有乱码，可以追踪到和他一起出现过在同一个地方超过5分钟的人。因为小红在昨天收到了 `zs8dA`，所以她会收到提醒消息。

整个过程其实挺简单的，但是挺有意思并且有效。

在其他相似的场景需求里，也是可以用到相似的用法的。

大家也可以放心下载 App，打开蓝牙，为控制疫情做出贡献。


## 参考

视频讲解：https://www.youtube.com/watch?v=D__UaR5MQao

漫画讲解：https://ncase.me/contact-tracing/

App官网：https://www.tracetogether.gov.sg/

