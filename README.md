# diffvm #

The diffvm is a differentable virtual machine，it include variable and operator, and their differentiate version. I want to make diffvm a common representation for learned program, and some tools for optimization and scheduler.

## 1.referene ##
- baselibrary: thread, io, memeory, communication, log, test...
- differentableware: variable, vector, matrix, operator, module(函数式编程语言/xshadow/tf/eigen/tensorlang)
- compiler: offline compiler for optimize and deploy program(tvm/xla)
- scheduler: online optimize and cooperate run(tf/mxnet/ray)
- toolkit: rl, pr, 3d, robotics
## 2.designdoc ##
1. baselib
2. tensorlang
