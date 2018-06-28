import argparse

parser = argparse.ArgumentParser()
parser.add_argument("word", help="give me a single word")
parser.add_argument("task", help="choose from uppercase lowercase length swapcase")
args = parser.parse_args()
print(args.word)
print(args.task)

word = args.word
if args.task == "uppercase":
    word = word.upper()
elif args.task == "lowercase":
    word = word.lower()
elif args.task == "length":
    word = len(word)
elif args.task == "swapcase":
    word = word.swapcase()
else: word="you entered an unsupported task"

print(word)
