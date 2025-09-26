# Задание 1

x = float(input("Введите число x: "))
y = 7 * x**2 - 2 * x + 5
print("Результат y =", y)

# Задание 2

m = int(input("Введите число m: "))
n = int(input("Введите число n: "))
q = int(input("Введите число q: "))
is_divisible = (m % n == 0) and (m % q == 0)
print(is_divisible)
