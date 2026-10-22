# dsa-from-scratch

![tests](https://github.com/yusvfcodez/dsa-from-scratch/actions/workflows/tests.yml/badge.svg)

Most of us learn data structures by using them. This repo is about building them.

Each structure and algorithm here is implemented from first principles in Python, with its cost written down and its edge cases tested. The aim is to understand why they behave the way they do.

## The rules
- **No shortcuts.** The structure under test is built without the built-in container it replaces. Built-ins appear only in tests, as the reference to check against.
- **Break it on purpose.** Every module is tested on normal cases and the nasty ones: empty input, a single element, duplicates, resize boundaries.
- **Know the cost.** Time and space complexity are stated in each module's docstrings.

## Try it
```bash
python -m venv .venv && source .venv/bin/activate
pip install pytest
pytest
```

## Layout
```
src/      implementations, one module per structure or algorithm
tests/    pytest tests, one file per module
```

## The roadmap
| Topic | Module | Status |
|---|---|---|
| Dynamic array (doubling resize) | `dynamic_array` | Planned |
| Hash map (chaining, resize) | `hash_map` | Planned |
| Merge sort, counting sort, radix sort | `sorting` | Planned |
| Stack, queue, binary search | `stack_queue`, `binary_search` | Planned |
| Linked lists (singly, doubly) | `linked_list` | Planned |
| Binary search tree | `bst` | Planned |
| AVL tree | `avl` | Planned |
| Trie | `trie` | Planned |
| Binary min-heap, heap sort | `heap` | Planned |
| Backtracking (subsets, permutations, N-Queens) | `backtracking` | Planned |
| Graph, BFS | `graph` | Planned |
| DFS, topological sort, union-find | `graph_algos` | Planned |
| Dijkstra, Bellman-Ford | `shortest_paths` | Planned |

A row becomes "Done" only when its module and tests are committed and passing.

## License
MIT
