#python 3

'''
Problem Statement

Given an array, find the int that appears an odd number of times.

There will always be only one integer that appears an odd number of times.
'''

def find_it(seq):
#starts with first character in list and iterates through
#until it finds a character used an odd number of times
    for i in seq:
        count = 0
        for j in seq:
            if j == i:
                count += 1
            else:
                count = count
        if count%2:
            return i
