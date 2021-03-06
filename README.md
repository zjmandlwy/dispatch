# dispatch

2018/4/6/粒子中间状态可视化
------------
粒子移动过程如下图<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/1.gif" width=500>
<br>
采用的测试函数是Griewank函数<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/Griewank.jpg" width=500>

2018/4/5/学习因子线性修改
------------

学习因子c1,c2决定了粒子本身经验和群体经验对粒子运动轨迹影响，C1先大后小，C2先小后大。基本思想参考前期主要靠粒子本身的历史信息，后期更加注重社会信息。<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/studychange.png" width=500>

2018/4/5/采用非线性惯性权重策略
------------

针对pso算法使用时线性递减容易陷入局部最优，采用一种非线性动态惯性权重方法<br>
<img  src="https://github.com/wangqifan/dispatch/blob/master/psoniw.png" width=500>

2018/4/4/二更
-----------

克服线性递减陷入局部最优的局限性采用微分递减策略
<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/des.PNG" width=500>

2018/4/4/更新
------------

采用线性惯性权重策略更新惯性权重线性递减策略目前应用最广泛，该方法使pso更好控制全局搜索和局部搜索能力，加快了收敛速度，提高了算法的性能<br>
线性递减策略迭代20次<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/linear.PNG" width=500>
<br>
对比权重不变，线性递减的收敛速度更快


2018/4/3/更新
-----------
使用python实现粒子群优化算法
<br>
20次迭代
<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/20.PNG" width=500>
<br>
50次迭代
<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/50.PNG" width=500>
<br>
100次迭代
<br>
<img src="https://github.com/wangqifan/dispatch/blob/master/100.PNG" width=500>

<br>

