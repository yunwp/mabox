###内置教程
- 需用到工具np或者mt
- 修改软件内置源，改软件图标，替换系统菜单图标和修改软件名等操作
-np（MT）管理器中打开安装包，在res文件夹内找到
如图标 原包里的图标名5j.png 需先改名，如 “5j1.png”，然后在导入相同名的图标名5j.png。一看就知道了
桌面图标：5j.png 设置菜单：7A.png 直播菜单：E1.png搜索菜单：NR.png历史菜单：Yu.png 背景图片：o8.png
###内置链接方法：
np（mt)管理器中打开安装包，找到 classes.dex文件，打开方式 “Dex编辑器++”
发起新搜索 查找内容 HomeActivity
找到 com.github.tvbox.osc.ui.activity 目录下的 HomeActivity 文件
打开 HomeActivity 文件，右上方按钮点开搜索 const-string v5,""
内置的源地址输入到" "引号中就完成了内置源。按 Esc 保存并退出，最后点安装包 “功能” 签名
一般情况下都能成功
