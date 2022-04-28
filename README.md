# Effective  C++
## 改善程序与设计的55个具体做法
1. [让自己习惯 C++](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Accustoming%20Yourself%20to%20C%2B%2B)
- 01 [视 C++ 为一个语言联邦](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Accustoming%20Yourself%20to%20C%2B%2B/01)
- 02 [尽量以 const , enum, inline 替换 #define](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Accustoming%20Yourself%20to%20C%2B%2B/02)
- 03 [尽可能使用 const](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Accustoming%20Yourself%20to%20C%2B%2B/03)
- 04 [确定对象被使用前已先被初始化](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Accustoming%20Yourself%20to%20C%2B%2B/04)

2. [构造，析构，赋值运算](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs%2C%20Destructs%2C%20and%20Assignment%20Operators)
- 05 [了解 C++ 默默编写并调用哪些函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/05)
- 06 [若不想使用编译器自动生成的函数，就该明确拒绝](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/06)
- 07 [为多态基类声明 virtual 析构函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/07)
- 08 [别让异常逃离析构函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/08)
- 09 [绝不在构造和析构过程中调用 virtual 函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/09)
- 10 [令 operator= 返回一个 *reference to* ***this**](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/10)
- 11 [在 operator= 中处理 “自我赋值”](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/11)
- 12 [复制对象时勿忘其每个成分](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Constructs,%20Destructs,%20and%20Assignment%20Operators/12)

3. [资源管理](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management)
- 13 [以对象管理资源](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management/13)
- 14 [在资源管理类中小心 *copying* 行为](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management/14)
- 15 [在资源管理类中提供对原始资源的访问](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management/15)
- 16 [成对使用 new 和 delete 时要采用相同形式](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management/16)
- 17 [以独立语句将 newed 对象置入智能指针](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Resource%20Management/17)

4. [设计与声明](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations)
- 18 [让接口容易被正确使用，不易被误用](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/18)
- 19 [设计 class 犹如设计 type](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/19)
- 20 [宁以 pass-by-reference-to-const 替换 pass-by-value](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/20)
- 21 [必须返回对象时，别妄想返回其 reference](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/21)
- 22 [将成员变量声明为 private](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/22)
- 23 [宁以 non-number、non-friend 替换 member 函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/23)
- 24 [若所有参数皆需类型转换，请以此采用 non-member 函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/24)
- 25 [考虑写出一个不抛出异常的 swap 函数](https://github.com/yuedaokong/Effective-Cpp-Learing/tree/main/Designs%20and%20Declarations/25)

5. [实现]
- 26 [尽可能延后变量定义式的出现时间]
- 27 [尽量少做转型动作]
- 28 [避免返回 handles 指向对象内部成分]
- 29 [为 “异常安全” 而努力是值得的]
- 30 [透彻了解 inlining 的里里外外]
- 31 [将文件间的编译依存关系降到最低]

6. [继承与面向对象设计]

7. [模板与泛型编程]

8. [定制 new 和 delete]

9. [杂项讨论]      
