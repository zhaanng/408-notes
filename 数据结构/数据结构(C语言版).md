# 链表
## 单链表
### 一、链表的定义
/*
定义链表，
本质上是是定义每个结点node里包含的东西，
有数据域和指针域，来保证结点存在有效数据和下一个结点的地址
*/
//定义链表数据域的数据类型为ElemType
typedef int ElemType;

typedef struct node{
	ElemType data;
	struct node* next;
}Node;


