shang_pin_info = {
101:{'name':'倚天剑','price':10000},
102:{'name':'屠龙刀','price':10000},
103:{'name':'九阳神功','price':10000},
104:{'name':'九阴白骨爪','price':9999},
105:{'name':'乾坤大挪移','price':8888},
106:{'name':'七伤拳','price':7777},
}

prompt='''******
商店
*********
按１购买
按２结算
'''
item=int(input(prompt))
# if item =='1':
#     print('*'*50)
#     for key,value in shang_pin_info.items():
#         print('%d   22  %s   22  %d'%(key,value['name'],value['price']))
#     print('*'*50)
# elif item=='2':
#     pass
while True:
    if item == '1':
            print('*'*50)
            for key,value in shang_pin_info.items():
                print('%d     %s     %d' % (key,value['name'],value['price']))
            print('*'*50)





'''
函数
'''
# def 函数名称(形参)；
#     函数体
# 调用函数
# 函数名称(实参)
# 参数　调用着传递给定义着的信息
# 返回值　定义着传递给调用这的结果　
# def fun01(a,b,c):
#     print(a)
#     print(b)
#     print(c)
# fun01(1,2,3)
# list01=[4,5,6]
# fun01(*list01)
# fun01(a=1,c=3,b=2)
# dict01={'a':1,'b':2,'c':3}
# fun01(**dict01)
# def fun02(a=0,b=0,c=0):
#     print(a)
#     print(b)
#     print(c)
# fun02()
# fun02(c=10)
# def fun03(*args):
#     print(args)
#     print(*args)
# fun03(1,2,4,5,6,7)
# def fun04(**kwargs):
#     print(kwargs)
#     for k,v in kwargs.items():
#         print(k,v)
# fun04(a=1,b=2,c=3)
# def fun05(*,name):
#     print(name)
# fun05(name=122)