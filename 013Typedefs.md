# C
# Typedefs

## Basic Example

A ```typedef``` is a way to define your own costumized type. It is generally used to make clearer and cleaner code.

```cpp
typedef int Length;
```
```cpp
Length my_length = 4;
printf("My length is %d\n", my_length);
```

### With Enum

```cpp
// You could write:
enum Gender {MALE, FEMALE};
typedef enum Gender Gender;

// OR you could write
typedef enum {MALE, FEMALE} Gender;
```
```cpp
Gender my_gender = FEMALE;
```

### With Array
```cpp
typedef double Real;
typedef Real Point3D[3];
```
```cpp
Point3D p,q;
Real p_x = 4.8;
p[0] = p_x;
```

