# alignment

## task

```cpp
struct A {
  int x;
  double y;
  short z;
  char w;
}; // sizeof - ???, alignof - ???


```

## build

```bash
cmake -H. -B_builds
cmake --build _builds/
./_builds/alignment
```
