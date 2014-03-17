# iTerm2 Tips

[http://www.waerfa.com/iterm2](http://www.waerfa.com/iterm2)

iTerm2是一款支持多标签、中键复制粘贴的Terminal替代型工具，我们在网上偶然看到了阿里工程师 fooCoder 在他的博客上分享的iTerm2使用体验短记，非常受用，在经过作者的授权后，我们得以把这些心得放在玩儿法上与大家分享，下面就来看看fooCoder是怎么玩转iTerm2的吧：

iTerm2的主要特点：

开源免费。
兼容性比默认Terminal更好。对于经常要远程使用的情况下，默认的Terminal在使用vi时经常出现不兼容的问题，而iTerm2在这方面显然做的更好。
快捷键丰富。

 - ⌘ + 数字: 切换标签页。 ⌘ + 方向键 按方向切换标签页。
 - ⌘ + enter: 切换全屏
 - ⌘ + f: 查找。支持正则。其中查找的内容会被自动复制。省去了再去⌘+c的步骤。同样，鼠标去选中的内容也会自动复制，也可以鼠标中键直接粘贴。一般在使用时，键入搜索关键词，然后用shift-tab或者tab左右自动补全，option + enter则自动将搜索结果键入，并且复制到剪贴板。
 - ⌘ + d: 垂直分屏，⌘ + shift + d: 水平分屏。使用⌘ + ]和⌘ + [在最近使用的分屏直接切换.而⌘ + opt + 方向键切换到指定位置的分屏。
 - ⌘ + t :新的标签页
 - ⌘ + w :关闭当前标签页
 - ⌘ + ；:自动补全历史命令。如图:自动补全
 - ⌘ + shift + h: 剪贴板历史，如图：剪贴板历史
 - ctrl + u: 清空当前行。这里要注意，mac默认的ctrl+u为清楚当前光标至行首的内容，在iTerm2中则直接清除本行。iTerm2 也支持其他常用的操作命令，这里顺带讲下，因为这些命令都是mac下非常常用也很好用的：ctrl + a: 到行首
 - ctrl + e: 行末
 - ctrl + f/b: 前进后退，相当于左右方向键，但是显然比移开手按方向键更快
 - ctrl + p: 上一条命令，相当于方向键上
 - ctrl + r: 搜索命令历史，这个大家都应该很熟悉了
 - ctrl + d: 删除当前字符
 - ctrl + h: 删除之前的字符
 - ctrl + w: 删除光标前的单词
 - ctrl + k: 删除到文本末尾
 - ctrl + t: 交换光标处文本⌘ + —/+/0: 调整字体大小
 - ⌘ + r:清屏，其实是滚到新的一屏，并没有清空。ctrl + l 也可以做到。
 - 更多实用功能：Exposé 标签 按⌘ + opt + e 打开Exposé，并支持搜索。如图：Exposé
 - 全局呼出快捷键。如图： 呼出快捷键
 - ⌘ + /: 找到当前光标位置，有时会很有用。
 - shift + ⌘ + s: 保存当前窗口快照。
 - ⌘ + opt + b: 快照回放。很有意思的功能，你可以对你的操作根据时间轴进行回放。可以拖动下方的时间轴，也可以按左右方向键。如图：快照回放
 - 支持256色。方便配置vi配色。但是在某些远超服务器上不支持256色，则只要在Prefences->Profiles->Terminal里设置为xterm。
 - 