---
title: "美妙系列-VoceChat聊天机器人接入监控移动报警"
date: 2023-05-29T11:37:57Z
draft:  false
tags: ["美妙"]
series: ["美妙"]
categories: ["美妙"]
--- 
这个系列第二个作品，聊天机器人接入监控移动报警
世界上有很多聊天软件，于是诞生了很多负责聊天的机器人。
本文只介绍最近刚入手的一款小而美的聊天服务器，支持一个更精简的聊天机器人
目前文档很全在这里https://doc.voce.chat/zh-cn
以下是视频介绍
 
 
{{< bili "http://player.bilibili.com/player.html?aid=871254775&bvid=BV1EV4y1t72g&cid=1208975589&page=1" >}}
 
 
[我网盘视频](http://pan.ezdial.cn/nasone/%e7%be%a4%e6%99%96/20230724274002%20%28online-video-cutter.com%29%20%281%29.mp4?v) 
- 代码源1. [个人网盘](http://pan.ezdial.cn/nasone/群晖)
- 代码源2. https://github.com/wjcroom/hi
 学习步骤：
1. 完成基本在vocechat-server的搭建
https://doc.voce.chat/zh-cn/
2. 了解机器人的用法
https://doc.voce.chat/zh-cn/bot/bot-and-webhook
3. 通过swagger工具创建和使用一些api
http://yourserver.ip:3000/api/swagger
4. 了解和使用自己摄像头在事件通知，日志记录方式
5. 使用一种登陆摄像头的方法捕获移动事件
