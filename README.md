# youssef-mhamedi-
import random 
secret =random.randint(1,100)
for i in range(10):
  x=int(input("9der:"))
  if x==secret:
    print("nice")
    break
  elif x < secret:
    print("igi")
else:
  print("izar")
