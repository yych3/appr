角色羽翼外观
===


```
命令
SETREPRESSDEMONWINGLOOK　A
```

|           |                   |
| --------- | ----------------- |
| **A参数代码** | **外观样式**          |
| 1     | ![](wing/1.jpg)   |
| 2     | ![](wing/2.jpg)   |
| 3     | ![](wing/3.jpg)   |
| 4     | ![](wing/4.jpg)   |
| 5     | ![](wing/5.jpg)   |
| 6     | ![](wing/6.jpg)   |
| 7     | ![](wing/7.jpg)   |
| 8     | ![](wing/8.jpg)   |
| 9     | ![](wing/9.jpg)   |
| 10    | ![](wing/10.jpg)  |
| 11    | ![](wing/11.jpg)  |
| 12    | ![](wing/12.jpg)  |
| 13    | ![](wing/13.jpg)  |
| 14    | ![](wing/14.jpg)  |
| 15    | ![](wing/15.jpg)  |
| 100   | ![](wing/100.jpg) |
| 101   | ![](wing/101.jpg) |
| 102   | ![](wing/102.jpg) |
| 103   | ![](wing/103.jpg) |
| 104   | ![](wing/104.jpg) |
| 105   | ![](wing/105.jpg) |
| 106   | ![](wing/106.jpg) |
| 107   | ![](wing/107.jpg) |
| 108   | ![](wing/108.jpg) |
| 109   | ![](wing/109.jpg) |
| 110   | ![](wing/110.jpg) |
| 111   | ![](wing/111.jpg) |
| 112   | ![](wing/112.jpg) |
| 113   | ![](wing/113.jpg) |
| 114   | ![](wing/114.jpg) |
| 115   | ![](wing/115.jpg) |
| 116   | ![](wing/116.jpg) |
| 117   | ![](wing/117.jpg) |
| 118   | ![](wing/118.jpg) |
| 119   | ![](wing/119.jpg) |
| 120   | ![](wing/120.jpg) |
| 121   | ![](wing/121.jpg) |
| 122   | ![](wing/122.jpg) |
| 123   | ![](wing/123.jpg) |
| 124       | ![](wing/124.jpg) |
| 125       | ![](wing/125.jpg) |


说明

官方在最新的客户端增加羽翼系统，取消了绿色封号的翅膀，请使用此命令设置人物翅膀。

使用此命令设置翅膀后，还要手动选择显示翅膀，否则游戏内不显示的。方法：F12--系统设置--个性设置--社会关系--勾选"显示翅膀"，确定即可。

如图：

![](wing/QQ截图20210805171554.jpg)


使用示例:
```
[@例]
#IF
CHECKJOB WARR
CHECKLEVELEX = 46
#ACT
FENGHAO 1 战将
SETREPRESSDEMONWINGLOOK 1
break
#IF
CHECKJOB WIZARD
CHECKLEVELEX = 46
#ACT
FENGHAO 1 法魂
SETREPRESSDEMONWINGLOOK 1
break
#IF
CHECKLEVELEX < 46
#ACT
break
#IF
CHECKJOB TAOIST
CHECKLEVELEX = 46
#ACT
FENGHAO 1 道玄
SETREPRESSDEMONWINGLOOK 1
break
```