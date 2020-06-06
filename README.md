okex.account_api   资金账户API

okex.futures_api   交割合约API

okex.lever_api   币币杠杆API

okex.spot_api   币币API

okex.swap_api   永续合约API

okex.index_api   指数API

okex.option_api   期权合约API

okex.system_api   获取系统升级状态

okex.consts   保存常用变量

okex.utils   公用工具

okex.client   登录使用

okex.exceptions   错误情况判断

---

如何使用？

强烈建议用户使用前阅读 Read before use.txt

第一步：下载代码及版本要求

1.1 建议python版本3.6+  使用WebsocketAPI时 建议websockets库为6.0版本

第二步：配置自己的API key

2.1 代码内默认没有key, 用户测试调用需要配置自己的相关信息

第三步：调用相关接口，在项目根目录下，找到相应文件

3.1 使用RestAPI
    
    参阅调试example.py
    
3.2 使用WebsocketAPI

    参阅调试websocket_example.py
    
附言：
1. 如果对API不太了解，建议可以先去参考OKEx官方api文档

    https://www.okex.com/docs/zh/

2. 关于ws的相关问题请参阅同级目录下 WS-May be could help you.txt文件



If you get a little confused：

websockets 入门文档： https://websockets.readthedocs.io/en/stable/intro.html
websockets python github： https://github.com/aaugustin/websockets
websockets 常见问题： https://websockets.readthedocs.io/en/stable/faq.html#client-side
关于code=1006错误：
https://github.com/Rapptz/discord.py/issues/1996
https://github.com/aaugustin/websockets/issues/587
使用asyncio开发： https://docs.python.org/3/library/asyncio-dev.html



1. 调用我们的接口均需要科学上网
服务器建议 香港阿里云

2. v3 api文档地址： https://www.okex.com/docs/zh/
申请v3API网址： https://www.okex.com/account/users/myApi

3. 若使用ws中遇到问题可参考同级目录下 May be could help you.txt 文件

PS：SDK仅为给予参考，降低开发门槛，相关客户端程序代码问题，还需本地调试解决，有帮助不到的地方，望多包涵。
---


---

<div align=center>

<img src="https://i.loli.net/2020/06/06/5XZ3rWicP9DsAv8.jpg" width="200" height="300">
</div>

--- 


<div align=Left>
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
</div>

<div align=center>
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
</div>

<div align=right>
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
</div>

这是一段普通的文本，<br>
直接回车不能换行，<br>
要使用<br>

这是一段普通的文本，

直接回车不能换行，

要使用

![Xnip2020-03-25_20-51-19.jpg](https://i.loli.net/2020/05/03/WmM9cTkoi1lIfuK.jpg)

![IMG_1826.JPG](https://i.loli.net/2020/06/06/5XZ3rWicP9DsAv8.jpg)