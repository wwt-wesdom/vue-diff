## patch算法判断是不是相同节点
1、key相同(vNode1.key === vNode2.key)
2、选择器相同（vNode1.sel === vNode2.sel）

## 更新策略-四种命中查找-命中一种就不再进行命中判断了
1、新前旧前
2、新后旧后
3、新后旧前（此种情况发生涉及到移动节点，那么新前指向的节点，移动到旧后之后）
4、新前旧后（此种情况发生涉及到移动节点，那么新前指向的节点，移动到旧前之前）
