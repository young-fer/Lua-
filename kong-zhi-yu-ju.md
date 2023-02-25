# 控制语句

### 循环

#### while循环

```lua
while(condition)
do
   statements
end
```

#### for循环

```lua
for var=exp1,exp2,exp3 do  
    <执行体>  
end
//var 从 exp1 变化到 exp2，每次变化以 exp3 为步长递增 var，并执行一次 "执行体"。exp3 是可选的，如果不指定，默认为1。
```

> 示例

```lua
for i = 1, 10, 2 do
    print(i, " ")
end

--[[
输出结果:
1        
3
5
7
9
]]
```

### 条件

#### if语句

```lua
if(布尔表达式)
then
   --[ 在布尔表达式为 true 时执行的语句 --]
end
```

#### if...else语句

```lua
if(布尔表达式)
then
   --[ 布尔表达式为 true 时执行该语句块 --]
else
   --[ 布尔表达式为 false 时执行该语句块 --]
end
```



