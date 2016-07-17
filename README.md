# pythonzis
import turtle
from math import sin

t = turtle.Turtle()
t.shape("turtle")
t.color("darkgreen", "yellow")
t.shapesize(1)
t.speed(10)

def main():
    t.penup()
    t.backward(350)

    digit_one(50)
    t.forward(60)
    digit_two(50)
    t.forward(60)
    digit_three(50)
    t.forward(60)
    digit_four(50)
    t.forward(60) 
    digit_five(50)
    t.forward(60) 
    digit_six(50)
    t.forward(60) 
    digit_seven(50)
    t.forward(60) 
    digit_eight(50)
    t.forward(60) 
    digit_nine(50)
    t.forward(60) 
    digit_zero(50)
    t.forward(60) 


    
    t.hideturtle()

    

def digit_one(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [90, 0, 135]
    A = [ L1,   L1, L2]

    t.forward(L1)
    t.pendown()
    for lenght, degree in zip(A, B):#змейка, молния в паре
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup() 

def digit_two(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [180, -135, 45, 90]
    A = [ L1,   L2, L1, L1]

    t.penup()
    t.forward(L1)
    t.pendown()
    for lenght, degree in zip(A, B):#змейка, молния в паре
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()
    
def digit_three(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [45, 135, -135, 135]
    A = [ L2,   L1, L2, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()
    
def digit_four(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [90, 0, 180, 270, 270]
    A = [ L1,   L1, L1, L1, L1]

    t.forward(L1)
    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()

def digit_five(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [0, 90, 90, 270, 270]
    A = [ L1,   L1, L1, L1, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()

def digit_six(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [0, 90, 90, 225, 180, 45]
    A = [ L1,   L1, L1, L2, L2, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()

def digit_seven(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [45, 45, 90]
    A = [ L2,   L1, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup() 
def digit_eight(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [0, 90, 0,90, 90, 90, 180, 90]
    A = [ L1,   L1, L1, L1,   L1, L1,L1,   L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()
def digit_nine(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [0, 90, 0,90, 90, 90]
    A = [ L1,   L1, L1, L1,   L1, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()  
def digit_zero(length):
    """ Рисует цифру с высотой length
        слева от направления черепашки
        контракт (договорённость):
            черепаха возвращается в исходную точку
            и имеет исходную ориентацию
            перо оказывается поднятым по окончании функции
    """
    L1 = length/2
    L2 = (length/2)*2**0.5
    B = [0, 90, 0,90, 90,0]
    A = [ L1,   L1, L1, L1,   L1, L1]

    t.pendown()
    for lenght, degree in zip(A, B):
        t.left(degree)
        t.forward(lenght)
    A.reverse()
    B.reverse()
    for lenght, degree in zip(A, B):
        t.backward(lenght)
        t.right(degree)
    t.penup()  
    
main()

