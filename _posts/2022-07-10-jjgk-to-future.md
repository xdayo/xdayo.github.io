---
layout: post
title: 由全国甲卷看未来高考的新趋势
date: 2022-07-10
tags: [数学]
author: 笑看山河 鑫鑫
license: CC-BY-NC 4.0 Intl
---

2022年高考全国甲卷理科数学第16题：

**16.** 已知$\triangle ABC$中，点$D$在边$BC$上，$\angle ADB=120^{\circ},AD=2,CD=2BD$，当$\frac{AC}{AB}$取得最小值时，$BD$=？

---

首先我们先回顾一下**高考命题思想**：坚持“有助于高校科学公正地选拔人才，有助于推进普通高中课程改革，实施素质教育”的原则，体现普通高中课程标准的基本理念，以能力立意，将知识、能力和素质融为一体，全面检测考生的数学素养，发挥数学作为主要基础学科的作用，考查考生对中学数学的基础知识、基本技能的掌握程度，考查考生的数学思想方法和数学本质的理解水平，以及进入高等学校继续学习的潜能。

---

针对这道题，如何解决呢？首先要画图（见图1）。设$BD=x$，则$CD=2x$，那么在$\triangle ADB$中，我们就可以用余弦定理，$(AB)^2=x^2+2^2-4xcos \angle ADB=x^2+4+2x$，同理可得，$(AC)^2=4x^2+4-4x$，$\frac{(AC)^2}{(AB)^2}=\frac{4x^2+4-4x}{x^2+4+2x}$，当$\frac{AC}{AB}$取最小值时，$\frac{(AC)^2}{(AB)^2}$也取最小值。设$g(x)=\frac{4x^2+4-4x}{x^2+4+2x}$，那么转换为求$g(x)$的极值。$g'(x)=0$，$g'(x)=\frac{(8x-4)(x^2+4+2x)-(4x^2+4-4x)(2x+2)}{(x^2+4+2x)^2}=0$。即$x^2+2x-2=0$，$\therefore x=-\sqrt{3}-1$（舍去），或$x=\sqrt{3}-1$，$\therefore BD=\sqrt{3}-1$，后面讨论略。

---

**本题考查的知识点有**：

1. 画图，设定$BD=x$

2. 余弦定理

3. 构造函数$g(x)$

4. 用求导的方法求$g(x)$的最小值，也就是使$g'(x)$为0，求出$x_0$，再判断$g(x_0)$是最小值还是最大值

此题是多个知识点的灵活运用，考查学生的知识、能力及素质，全面检测考生的数学素养，紧扣高考命题思想，未来的高考命题必将是多个知识点的综合运用，尤其是构造函数，对考生难度较大。

---

[![](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/deed.zh)

本文章采用[CC-BY-NC 4.0国际](https://creativecommons.org/licenses/by-nc/4.0/deed.zh)协议进行许可(不包括引用的知识共享许可证徽章)。

[联系作者](mailto:email@xilong.tk) · [侵权联系](mailto:tort@xilong.tk) —— 分享 · [QZone](https://sns.qzone.qq.com/cgi-bin/qzshare/cgi_qzshare_onekey?url=https%3A%2F%2Fblog.xilong.tk%2Fjjgk-to-future%2F&title=%E7%94%B1%E5%85%A8%E5%9B%BD%E7%94%B2%E5%8D%B7%E7%9C%8B%E6%9C%AA%E6%9D%A5%E9%AB%98%E8%80%83%E7%9A%84%E6%96%B0%E8%B6%8B%E5%8A%BF&site=%E7%AC%91%E7%9C%8B%E5%B1%B1%E6%B2%B3%E7%9A%84%E5%8D%9A%E5%AE%A2) · [Weibo](https://service.weibo.com/share/share.php?url=https%3A%2F%2Fblog.xilong.tk%2Fjjgk-to-future%2F&count=1&title=%E7%94%B1%E5%85%A8%E5%9B%BD%E7%94%B2%E5%8D%B7%E7%9C%8B%E6%9C%AA%E6%9D%A5%E9%AB%98%E8%80%83%E7%9A%84%E6%96%B0%E8%B6%8B%E5%8A%BF&language=zh_cn)
