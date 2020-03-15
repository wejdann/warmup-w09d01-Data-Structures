# Data Structures

## Arrays

## Linked List


## Stack 
Operate on “last-in, first-out”(LIFO)behavior. The last, most recently added item, is the first to be removed.
#### Example: 
 “back” button on your browser.
 #### Big O
| Function  | Complexity|
| ------------- | ------------- |
| Access | O(1) |
| Insert | O(1)  |
| Delete  | O(1)  |
| Check empty | O(1) |


## Queues
Operate on “first-in, first-out”(FIFO) behavior. Items are removed in the order they were added, from first to last.
#### Example: 
The ordeer of print document using FIFO.
#### Big O:
| Function  | Complexity|
| ------------- | ------------- |
| Access | O(1) |
| Insert | O(1)  |
| Delete  | O(1)  |
| Check empty | O(1) |

## Hash Tables 

## Sets

## Binary Trees

A binary tree is made of nodes, where each node contains a "left" reference, a "right" reference, and a data element. The topmost node in the tree is called the root.

Binary trees are used to represent a nonlinear data structure. There are various forms of Binary trees. Binary trees play a vital role in a software application. One of the most important applications of the Binary tree is in the searching algorithm.

Big(O):
Average Case: O(log n)
Worst Case: O(n)

## Tries

## Balancing Binary Trees (AVL Tree)

AVL tree is a binary search tree in which the difference of heights of left and right subtrees of any node is less than or equal to one. The technique of balancing the height of binary trees was developed by Adelson, Velskii, and Landi and hence given the short form as AVL tree or Balanced Binary Tree.

AVL trees are used for frequent insertion. One of the examples I know of is it is used in Memory management subsystem of linux kernel to search memory regions of processes during preemption.

Big(O):
Average Cae: O(log n)
Worst Case: O(log n)
