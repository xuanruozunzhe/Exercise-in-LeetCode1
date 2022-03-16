# Exercise-in-LeetCode1
二分查找、第一个错误的版本、搜索插入位置

1.1给定一个 n 个元素有序的（升序）整型数组 nums 和一个目标值 target  ，写一个函数搜索 nums 中的 target，如果目标值存在返回下标，否则返回 -1。
示例1：
输入: -1 0 3 5 9 12
9
输出: 4
解释: 9 出现在 nums 中并且下标为 4
示例2：
输入: -1 0 3 5 9 12
2
输出: -1
解释: 2 不存在 nums 中因此返回 -1

1.2你是产品经理，目前正在带领一个团队开发新的产品。不幸的是，你的产品的最新版本没有通过质量检测。由于每个版本都是基于之前的版本开发的，所以错误的版本之后的所有版本都是错的。
假设你有 n 个版本 [1, 2, ..., n]，你想找出导致之后所有版本出错的第一个错误的版本。
你可以通过调用 bool isBadVersion(version) 接口来判断版本号 version 是否在单元测试中出错。实现一个函数来查找第一个错误的版本。你应该尽量减少对调用 API 的次数。
示例1：
输入：5
4
输出：left=3mid=4
错误版本号为：4

1.3给定一个排序数组和一个目标值，在数组中找到目标值，并返回其索引。如果目标值不存在于数组中，返回它将会被按顺序插入的位置。
请必须使用时间复杂度为 O(log n) 的算法。
示例1：
输入: 1 3 5 6
5
输出: 2
示例2：
输入: 1 3 5 6
2
输出: 1
示例3：
输入: 1 3 5 6
7
输出: 4
示例4：
输入: 1 3 5 6
0
输出: 0

2.1给你一个按 非递减顺序 排序的整数数组 nums，返回 每个数字的平方 组成的新数组，要求也按 非递减顺序 排序。
示例1: 
输入: -6 -1 0 4
输出: [0, 1, 16, 36]
示例2: 
输入: -4 -3 0 3 5
输出: [0, 9, 9, 16, 25]

有序数组的平方、轮转数组

2.2给你一个数组，将数组中的元素向右轮转 k 个位置，其中 k 是非负数。
示例1：
输入:1 2 3 4 5 6 7
3
输出: [5,6,7,1,2,3,4]
解释:
向右轮转 1 步: [7,1,2,3,4,5,6]
向右轮转 2 步: [6,7,1,2,3,4,5]
向右轮转 3 步: [5,6,7,1,2,3,4]
示例2：
输入：nums = -1 -100 3 99
2
输出：[3,99,-1,-100]
解释: 
向右轮转 1 步: [99,-1,-100,3]
向右轮转 2 步: [3,99,-1,-100]
