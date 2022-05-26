# Data Structure and Algorithm

王卓数据结构与算法课程代码，根据严蔚敏版教材补充了部分代码（本文档中在对应cpp文件下备注了补充说明）

图往后课讲的很浅，省略了不少代码，我补充了一些，还有一些留个坑以后有时间补充

## 目录

### 1.Linear_List 线性表

sequentialList.cpp 顺序表

singleLinkList.cpp 单链表

doubleLinkList.cpp 双向链表

listUnion.cpp 线性表应用，未完成，排序算法结束后补充

### 2.Stack 栈

sqStack.cpp 顺序栈

linkStack.cpp 链栈

### 3.Queue 队列

sqQueue.cpp顺序队列

linkQueue.cpp链队列

### 4.String 串

string.cpp 串，包含串的模式匹配算法

备注：KMP算法部分用了几种不同的方式写next数组，可能跟王老师课的方法不一样，不过我都测试过，可以跑通

KMP.cpp KMP算法单独拆分出来，含测试代码

### 5.Binary_Tree 二叉树

binaryTree.cpp 二叉树

补充：统计度为1、2结点个数

HuffmanTree 哈夫曼树和哈夫曼编码

补充：select函数实现，哈夫曼树生成后遍历输出测试代码

### 6.Graph 图

graph.cpp 图

备注：本文件全部使用c++实现，栈、队列等使用STL

补充：

算法4.采用邻接表表示图的深度优先搜索遍历算法

算法5.深度优先搜索遍历非连通图

算法7.Prim算法实现最小生成树

算法8.Kruskal算法实现最小生成树 重点是理解连通分量

[留坑待填]最短路径、拓扑排序、关键路径以后再补充，有点费时间...

+++

### 7.Search 查找

search.cpp 查找

补充：

算法6.二叉排序树的删除

AVL_Tree.cpp 基于模板类的平衡二叉树实现 ==未完成==

[留坑待填]AVL树代码实现

[留坑待填]B-树

[留坑待填]B+树

### 8.Sort 排序

sort.cpp 排序

![img](https://raw.githubusercontent.com/xingzhe321/TyporaPic/master/img/202205261606140.png)