# 如何测量进程上下文切换的成本

OSTEP 第 6 章作业：
要求对进程上下文切换的成本（时间开销）进行测量。

题目描述见链接：https://pages.cs.wisc.edu/~remzi/OSTEP/Chinese/06.pdf

### 测量方式

1. 通过将进程绑核，确保上下文切换的进程跑在同一个处理器上。
2. 利用进程间双向通信，两个进程不断切换，通过反复测量这种通信成本，达到预估进程上下文切换成本的目的。

### 两个知识点

- 处理器亲和力
- 进程间通信-管道

什么是处理器亲和力？



### 扩展

lmbench工具

