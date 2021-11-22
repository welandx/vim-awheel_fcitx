# vim-awheel_fcitx

原插件支持的是fcitx4，修改了一下变量内容以适用于fcitx5

另外可以通过[vim-plug](https://github.com/junegunn/vim-plug)安装该插件：

```
Plug 'welandx/vim-awheel_fcitx'
```

---
Linux系统使用 **fcitx框架中文输入法** 会出现输入干扰,此插件用来解决这类问题

ps: 这里推荐在Linux系统使用 **谷歌拼音输入法** (Fcitx框架),因为我真的不想让搜狗输入法收集我的隐私.

本插件主要是为了解决Linux下使用vim时中文输入法干扰的问题

实现的功能如下:

1. 可以设置每次打开vim时的默认输入法(中文或英文)
2. 可以设置第一次进入插入模式时启用的输入法
3. 使用ESC键退出插入模式自动切为英文输入法
4. 当进入插入模式的时候会自动切为上一次插入模式使用的输入法
