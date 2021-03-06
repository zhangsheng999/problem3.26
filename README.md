# problem3.26

## Continue the previous problem,and construct the phase-space plots as in Figures3.16 and 3.17 in different regimes

##   （继续完成之前的题目，并且在不同的环境下构建Figure 3.16和Figure 3.17的相空间图像）

## 之前我们在课本中研究了洛伦兹模型，下面先介绍一下洛伦兹模型

### 洛伦兹 - 混沌理论之父
### 爱德华·诺顿·洛伦茨（英语：Edward Norton Lorenz，1917年5月23日－2008年4月16日），美国数学与气象学家。混沌理论之父，蝴蝶效应的发现者。1963年获美国气象学会迈辛格奖. 
### 罗伦兹毕业于达特茅斯学院、哈佛大学和麻省理工学院，生前在麻省理工任教。他于上世纪六十年代，提出了著名的“混沌理论（ChaosTheory）”，指小小的变化可产生巨大影响，例如巴西一只蝴蝶煽动翅膀这个看似微不足道的现象，可改变大气运动的方式，引发美国得州爆出龙卷风。此现象被称为“蝴蝶效应（Butterfly Effect）”。 
### 罗伦兹所提出的“决定性混沌（DeterministicChaos）”被指是自牛顿以来另一引人注目的人类自然观的“进化论”，他因此于一九九一年获颁基础科学京都奖。罗伦兹认为，人类本身都是非线性的：与传统的想法相反，健康人的脑电图和心脏跳动并不是规则的，而是混沌的，混沌正是生命力的表现，混沌系统对外界的刺激反应，比非混沌系统快得多。 
### “混沌理论”是在数学和物理学中，研究非线性系统在一定条件下表现出的现象的理论。一九六三年罗伦兹提出了该想法，以图解释非线性系统具有的多样性和多尺度性。“混沌理论”最大的贡献是用简单的模型来推出明确的非周期性结果。 
### 该理论认为在混沌系统中，初始条件十分微小的变化经过不断放大，对其未来状态会造成极其巨大的差别。例如马蹄铁上的一个钉子是否会丢失，本是初始条件十分微小的变化，但其“长期”效应却是一个帝国存与亡的根本差别。这就是所谓“蝴蝶效应”。 
### “蝴蝶效应”是指在一个动力系统中，初始条件下微小的变化能带动整个系统的长期而巨大的连锁反应。这是一种混沌现象，“一只蝴蝶在巴西轻拍翅膀，会使更多蝴蝶跟著一起振翅。最后将有数千只的蝴蝶都跟著那只蝴蝶一同挥动翅膀，其所产生的飓风可以导致一个月后在美国得州发生一场龙卷风。 ” 
### 在《混沌学传奇》等书中皆有这样的描述：“一九六一年冬季的一天，罗伦兹在计算机上进行关于天气预报的计算。为了考察一个很长的序列，他走了一条捷径，没有令计算机从头运行，而是从中途开始．他把上次的输出直接打入作为计算的初值，然后他穿过大厅下楼，去喝咖啡。一小时后他回来时，发生了出乎意料的事，他发现天气变化同上一次的模式迅速偏离，在短时间内，相似性完全消失了。进一步的计算表明，输入的细微差异可能很快成为输出的巨大差别。 
### 罗伦兹最初使用的是“海鸥效应”来形容这种现象，但在一九七九年于华盛顿的美国科学促进会的演讲上却问道：“一只蝴蝶在巴西搧动翅膀会在得克萨斯引起龙卷风吗？”“蝴蝶效应”因此得名。
   
   
 #### 由教材，大气物理学家Lorenz在研究Rayleigh-Benard问题时，将流体力学基本方程组Navier-Stokes方程组化简为简单形式：
 
 ![](https://github.com/zhaozhanyi0804/computationalphysics_N2015301020052/raw/master/Homework-8/8-1.jpg)
 
 
 ##### 以下展示不同系数r的情况下，z随时间变化的影响
 
 [代码](https://github.com/zhangsheng999/1111/blob/master/1.txt)
 
 ![](https://github.com/zhangsheng999/1111/blob/master/Figure_1.png?raw=true)
 
 
 ##### Figure 3.16——相空间中的混沌lorenz模型
 
 [代码](https://github.com/zhangsheng999/1111/blob/master/2.txt)
 
 ![](https://github.com/zhangsheng999/1111/blob/master/%E5%95%8A.png?raw=true)
 
 ###### 可以看到与书中Figure3.16一致
 
 
 ##### Figure 3.17——相空间中的混沌lorenz模型
 
 [代码](https://github.com/zhangsheng999/1111/blob/master/3.txt)
 
 
![](https://github.com/zhaozhanyi0804/computationalphysics_N2015301020052/raw/master/Homework-8/8-9.png)

###### 可以看到与书中Figure3.17一致


> * 致谢  吴雨桥同学 夏海峰同学提供的代码及帮助
 
