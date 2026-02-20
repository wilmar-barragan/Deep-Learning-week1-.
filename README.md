# Deep-Learning-week1-.
Entiende una neurona en 15 minutos (Red 'vainilla')

Para que la neurona funcione como una compuerta AND, los valores de b deben cumplir las siguientes condiciones, asumiendo w1=1 y w2=1:

Para las entradas (0,0), (0,1) y (1,0), la salida y debe ser 0. Esto significa que z (que es x1*w1 + x2*w2 + b) debe ser estrictamente menor que 0 (z < 0).

Para (0,0): 0*1 + 0*1 + b < 0 => b < 0
Para (0,1): 0*1 + 1*1 + b < 0 => 1 + b < 0 => b < -1
Para (1,0): 1*1 + 0*1 + b < 0 => 1 + b < 0 => b < -1
Para la entrada (1,1), la salida y debe ser 1. Esto significa que z debe ser mayor o igual que 0 (z >= 0).

Para (1,1): 1*1 + 1*1 + b >= 0 => 2 + b >= 0 => b >= -2
Combinando todas las condiciones (b < 0, b < -1, b < -1, y b >= -2), el rango de valores para b es -2 <= b < -1.

Esto significa que el valor de b puede ser cualquier número entre -2 (inclusive) y -0.1 (exclusivo). El máximo número posible que permite que la neurona funcione como una compuerta AND se acerca a -0.1, , el máximo sería -2.
