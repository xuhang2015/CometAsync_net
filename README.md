# CometAsync_net
C#实现基于http长连接“服务器推”-Comet技术<br/>
很多应用譬如监控、即时通信、即时报价系统都需要将后台发生的变化实时传送到客户端而无须客户端不停地刷新、发送请求。<br/>
本项目基于 AJAX 的长轮询方式实现。

<h4>CometAsyncService</h4>
服务端实现，主要包含Comet实现机制<br/>

<h4>CometAsyncClient</h4>
客户端实现，测试程序<br/>

测试截图
![image](https://raw.githubusercontent.com/xuhang2015/image_repos/master/%E6%8D%95%E8%8E%B7.PNG)
Cient是一个模拟即时通讯的一个简单控制台程序，使用方法如下：</br>
1 按"1"订阅；<br/>
2 输入你的名字，如“a1”;<br/>
3 与已订阅用户聊天，如有位订阅用户“a2”，你可输入：@a2|hello a1。
