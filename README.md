# Code01

### >using System;
### >using System.Collections.Generic;
### >using System.Linq;
### >using System.Text;
### >using System.Threading.Tasks;

### >namespace ConsoleApp1
### >>{
### >>>class Program
### >>>>{
### >>>>>static void Main(string[] args)
### >>>>>{
### >>>>>>System.Console.WriteLine("请输入num的值，回车结束");
### >>>>>>int num = Console.Read();             //定义并获取变量(值类型)
### >>>>>>String str = "not123";                //定义字符串类型变量（引用类型）
###
### >>>>>>if (num == 123)               //判断num是否有值           
### >>>>>>{ Console.WriteLine("num = " + num); }   //如果有值就输出num
### >>>>>> else
### >>>>>> { Console.WriteLine(str); }    //如果没有值就输出提示
###
### >>>>>> Console.ReadKey();       //防止闪退
### >>>}
### >>}
### >}

## 测试截图
![alt](code01\photo1.png)
![alt](code01\photo2.png)
