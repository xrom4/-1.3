# Лабораторная работа 1.3
 ## Task 1 (11)◦ Two nonzero numbers are given. Find the sum, difference, product and quotient of their modules ##
      a = random.uniform(-100,100)
      b = random.uniform(-100,100)
      print("a = ", a)
      print("b = ", b)
      abs_a = abs(a)
      abs_b = abs(b)
      print("Модуль a = ", abs_a)
      print("Модуль b = ", abs_b)
      print("Сумма модулей: ", abs_a + abs_b)
      print("Разность модулей: ", abs(abs_a - abs_b))
      print("Произведение модулей: ", abs_a * abs_b)
      print("Частное модулей: ", abs_a / abs_b)
 ## Task 2(11) -A three-digit number is given. Find the sum and product of its digits.
    import random
    N = random.randrange(100,1000)
    print("Число: ", N)
    d2 = int(N/100)
    d1 = int((N-d2*100)/10)
    d0 = N%10
    print("Сотни: ", d2)
    print("Десятки: ", d1)
    print("Единицы: ", d0)
    print("Сумма цифр: ", d0+d1+d2)
    print("Произведение цифр: ", d0*d1*d2)
 ## Task 3(11) Two integers are given: A, B. Check the truth of the statement: "The numbers A and B have the same parity."
    import random
    A = random.randrange(1,10)
    B = random.randrange(1,10)
    print("A = ", A)
    print("B = ", B)
    a1 = (A%2)==0
    b1 = (B%2)==0
    x = (a1 == b1)
    print("A четно: ", a1)
    print("B четно: ", b1)
    print("У чисел A и B одинаковая четность: ", x)
   
## Task 4(11) Two integer type variables are given: A and B. If their values are not equal, thenassign each variable the greater of these values, and if they are equal,then assign zero values to the variables. Output new values of variables A and B.

    A = int(input())
    B = int(input())
    if A != B:
    A = B = max(A, B)
    print (A, B)
    else:
    A = B = 0
    print (A, B)

