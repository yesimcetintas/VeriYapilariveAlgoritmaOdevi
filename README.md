# Insertion Sort Projesi
## Proje -1 -> Insertion Sort
### [22,27,16,2,18,6] 
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.  
[22,27,16,2,18,6]  
[22,27,16,2,18,6]  
[16,22,27,2,18,6]  
[2,16,22,27,18,6]  
[2,16,18,22,27,6]  
[2,6,16,18,22,27]  
2. Big-O gösterimini yazınız.  
Big O: O(n^2)  
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.  
Average case: O(n^2)  
Worst case: O(n^2)  
Best Case: O(n)  
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  
Dizi sıralandıktan sonra 18 sayısı 4. sırada bu yüzden average case kapsamına girmektedir.  
### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.  
[7,3,5,8,2,9,4,15,6]  
[3,7,5,8,2,9,4,15,6]  
[3,5,7,8,2,9,4,15,6]  
[3,5,7,8,2,9,4,15,6]
## Proje - 2 -> Merge Sort
1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
```
               [16,21,11,8,12,22]
                /             \  
         [16,21,11]          [8,12,22]  
          /      \            /      \  
     [16,21]     [11]      [8,12]    [22]  
     /     \        \       /    \      \  
 [16]     [21]     [11]  [8]     [12]   [22]  
    \     /         /       \    /      /  
    [16,21]      [11]       [8,12]    [22]  
        \        /            \       /  
        [11,16,21]            [8,12,22]  
              \                   /  
                [8,11,12,16,21,22]

 ```
2. Big-O gösterimini yazınız.  
Big O: O(nlog(n))
## Proje - 3 -> Binary Search Tree
1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.  
```
Root: 6 
                     6   
                   /   \  
                  5     7  
                 /       \  
                1         8  
               / \         \  
              0   3         9  
                 / \  
                2   4

```