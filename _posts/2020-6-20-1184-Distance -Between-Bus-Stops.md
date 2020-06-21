---
layout: post
title: LeetCode.1184. 
---
## Discription

---

A bus has n stops numbered from 0 to n - 1 that form a circle. We know the distance between all pairs of neighboring stops where distance[i] is the distance between the stops number i and (i + 1) % n.

The bus goes along both directions i.e. clockwise and counterclockwise.

Return the shortest distance between the given start and destination stops.

## Examples

---





**Example1:**

![img](https://assets.leetcode.com/uploads/2019/09/03/untitled-diagram-1.jpg)

> Input: distance = [1,2,3,4], start = 0, destination = 1
> Output: 1
> Explanation: Distance between 0 and 1 is 1 or 9, minimum is 1.

**Example2:**

![img](https://assets.leetcode.com/uploads/2019/09/03/untitled-diagram-1-1.jpg)

> Input: distance = [1,2,3,4], start = 0, destination = 2
> Output: 3
> Explanation: Distance between 0 and 2 is 3 or 7, minimum is 3.

**Example3:**

![img](https://assets.leetcode.com/uploads/2019/09/03/untitled-diagram-1-2.jpg)

> Input: distance = [1,2,3,4], start = 0, destination = 3
> Output: 4
> Explanation: Distance between 0 and 3 is 6 or 4, minimum is 4.

- **Constraints:** 
  - 1 <= n <=10^4^
  - distance.length == n
  - 0 <= start, destination < n
  - 0 <= distance[i] <= 10^4^

## Think

---

Loop, count the sum of all elements and calculate the distance between the two points (only one direction), and get the shortest distance by comparing (and - this value) and the size of this value.

## Solution

![_config.yml](../images/arith.png)

---

[来源:力扣（LeetCode)著作权归领扣网络所有。商业转载请联系官方授权，非商业转载请注明出处。](https://leetcode-cn.com/problems/distance-between-bus-stops)

