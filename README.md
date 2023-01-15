# zhupeixing.github.io
项目关键点：A/B test关键点
A/B测试背后的一个关键假设是，实验组和控制组之间的唯一区别在于我们正在测试的功能。这意味着实验组和控制组用户发布需要有可比性。如果这是真的，那么我们就可以准确地估计功能变化对我们实验的任何度量的影响。

可比性：实验组和控制组的用户分布是指，对于每个相关的细分市场，实验组和控制组用户的相对比例是相似的。

从纯统计的角度来看，上述情况在足够多的用户中是正确的。在A/B测试中，我们寻找的是非常小的增益，所以需要样本量足够大以保证测试组和控制组分布是相同的。

在日常实践中，经常会出现实验组和控制组分布不同，从而使实验结果无效的情况出现这种情况的首要原因是随机算法中的漏洞或偏差，在将用户分配给实验组和控制组时，导致某些特定的群体的代表性过度或不足。

因此，在进行统计测试之前，检查实验组和控制组分布是否相似是极其重要的。
