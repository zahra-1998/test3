# test3
#!/bin/bash


# Input:
# a, amount
# k, ka
# i, interest

# Output:
# sample cal = a*k*i

echo"Enter the amount:"
read a    
echo"Enter interest:"
read i    
echo"Enter ka:"
read k     

s=`expr $a \* $k \* $i / 100`    
echo"The test is: "
echo$s
