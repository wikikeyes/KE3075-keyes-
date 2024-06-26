
<span style="color: rgb(255, 76, 65); font-size: 30px;">**特别注意：本套件(产品)不包含课程中使用到的开发板，扩展板和USB线，需要另外购买。**</span>

<br>
<br>

**首先感谢选择keyes产品，我们将继续为你提供好的产品和服务!**

---

**关于keyes**   

Keyes是KEYES Corporation旗下最畅销的品牌，我们的产品包括Arduino开发板、扩展板、传感器模块；树莓派、micro：bit扩展板和智能小车；以及为各阶段客户设计的完整入门套件。这些入门套件旨在为任何水平的客户学习Arduino、树莓派、micro：bit相关知识。

我们所有产品，均符合国际质量标准，在世界各地不同市场中，得到了极大的赞赏。

欢迎从我们的官方网站查看更多内容：[http://www.keyes-robot.com](http://www.keyes-robot.com)

---

**售后服务**                     

1\. 如果发现某些东西丢失或损坏，或者学习套件时遇到一些困难，keyes会提供免费和快速的支持。如果您有任何疑问，请联系我们我们客服或工作人员。

2\. 欢迎提出建议和反馈，我们会根据您的反馈不断更新套件和教程，以使其更好。谢谢！

---

**产品安全**

1\. 本产品内含细小的元器件（电阻，LED等），请放在儿童接触不到的地方，防止划伤或误食。8岁及以下儿童使用，请在大人监督下使用。

2\. 本产品包含导电部件(控制板和电子模块），请按照本教程的要求进行操作，不当的操作可能导致过热并且损害零件，请勿触摸并立即断开电路电源。

---

**版权**  

keyes商标和徽标是KEYES DIY ROBOT co.,LTD的版权,任何人和公司在没有授权的情况下，不得复制，售卖，转卖，keyes品牌的产品。如果您有兴趣在当地售卖我们的产品，请联系我们专业的批发销售人员。

---

# Keyes 光线检测套件

![图片不存在](./media/0622f0b43c668fcf24c0dc2b3413160a.jpg)

---

## 产品介绍

光线检测套件集于光敏传感器、继电器模块、有源蜂鸣器模块、电阻和各种LED等模块与元件，通过Plus主板或Micro:Bit主板或树莓派Pico主板或ESP32主板或不配主板不编程进行控制。使用Arduino C 软件或MakeCode软件或Mixly软件或KidsBlock软件或Thonny软件进行编程，可以控制LED、蜂鸣器和其他模块工作，并且还可以通过读取光敏传感器检测的光照强度输出的模拟信号，来确定环境光(光照)强弱。如果检测到的光照强度大于设定值时，则蜂鸣器发出警报声，LED会闪烁，从而提醒人们此时的光照强度过强。通过这种方式，可以实现极大程度地降低能源损耗，光线检测报警系统适用于家庭或路灯或光控系统等场所。

---

## 清单

当收到这个Keyes光线检测套件的时候，首先看到是一个包装精美的外盒，每个配件被安全且有序的装在外盒里面的小袋子里，先来清点一下：

| 序号 | 名称 | 数量 | 图片 |
| :--: | :--: | :--: | :--: |
| 1 | 面包板 | 1 | ![图片不存在](./media/b7c6a61f9050e53f64bdeca423a32892.png)|
| 2 | 光敏传感器 | 1 | ![图片不存在](./media/64f4a9e4d9b86ff8b0ef8b66afabffe0.png) |
| 3 | 5V 单路继电器模块 | 1 | ![图片不存在](./media/1677c94f2390adeb3df19bfabd6ced88.png) |
| 4 | 有源蜂鸣器模块 | 1 | ![图片不存在](./media/08cac8e036b616593db2d11a13d7922d.png) |
| 5  |面包板专用电源模块|1|![图片不存在](./media/62ad1c318f4507c38556f376c502bbe9.png)|
| 6 | 220Ω电阻 | 10 | ![图片不存在](./media/83dd3936e779ba45cddf56600115789d.png) |
| 7 | 1KΩ电阻 | 10 | ![图片不存在](./media/9b934d4a221b3b257a455c3b3c4228e2.png)|
| 8 | 红色LED | 5 |![图片不存在](./media/28c28e6163de71f861c1f8f9bf621ee2.png)|
| 9 | 黄色LED | 5 | ![图片不存在](./media/538628fed136c06e104ae01b69774d34.png)|
| 10 | 蓝色LED | 5 |![图片不存在](./media/f6bbd58a5d3ad73cbbb4f9dc6dbebce0.png) |
| 11 | 绿色LED | 5 |![图片不存在](./media/cede9aadb081f8efbe1aa2884452296f.png) |
| 12 | 白色LED | 5 | ![图片不存在](./media/8aebcf71e0db1a7f97458ee667b22878.png)|
| 13 | 一字型螺丝刀  | 1 |![图片不存在](./media/f5504973a1c7bd3a74e8a9370a3c2358.png)|
| 14 |公对母杜邦线|1| ![图片不存在](./media/dda94299cc2abaff2c9cb8ff7ce365ff.jpg)|
| 15 |母对母杜邦线|1| ![图片不存在](./media/69e6d113c252cd1742d38913cb2f1b5b.png)|
| 16 | 面包板连接线 | 1 | ![图片不存在](./media/b146f1221b43b628375e658c8c0bc91f.png)|
| 17 |电阻卡 | 1 |![图片不存在](./media/443cb9da6e229e8e2ec048855e7dc367.png) |
| 18 | 电源适配器 | 1 | ![图片不存在](./media/20a54fcaa52b0e56f8f185644cad8c12.png)|

---

## 课程

* [1.UNO主板_C_教程](1.UNO主板_C_教程/UNO主板_C_教程.md)

* [2.UNO主板_KidsBlock_教程](2.UNO主板_KidsBlock_教程/UNO主板_KidsBlock_教程.md)

* [3.UNO主板_Mixly_教程](3.UNO主板_Mixly_教程/UNO主板_Mixly_教程.md)

* [4.Microbit主板_教程](4.Microbit主板_教程/Microbit主板_教程.md)

* [5.Pico主板_C_教程](5.Pico主板_C_教程/Pico主板_C_教程.md)

* [6.Pico主板_Python_教程](6.Pico主板_Python_教程/Pico主板_Python_教程.md)

* [7.Esp32主板_C_教程](7.Esp32主板_C_教程/Esp32主板_C_教程.md)

* [8.Esp32主板_Python_教程](8.Esp32主板_Python_教程/Esp32主板_Python_教程.md)

* [9.不配主板_不需编程_教程](9.不配主板_不需编程_教程/不配主板_不需编程_教程.md)

* [代码集](代码集.zip)

* [其他相关资料](其他相关资料.zip)

<span style="color: rgb(0, 209, 0);">**特别注意：所有教程的代码都在<span style="color: rgb(255, 76, 65);">代码集</span>压缩包里，学习课程之前一定要先下载解压。**<span style="color: rgb(0, 209, 0);"></span></span>

---
