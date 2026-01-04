# base11cv
Detecting Reused Destination Addresses
from collections import Counter
tos = Counter(tx["to"] for tx in block.transactions if tx["to"])
print(tos)
