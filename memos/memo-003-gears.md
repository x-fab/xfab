# Gears


Gears with a module of 1mm prints well on the Ultimakers.


## Design

When you print a gear, you don't want brim because it's practically hard to remove between teeth.
But when you remove it, a small elephant foot may appear.
```
--+
  |
  |
  |
  |
--+  desired profile


--+
  |
  |
  |
  \
---+  elephant foot
```

The solution I use is to add a 1.5mm fillet without support on the surface plate.

```
--+
  |
  |
  |
  |
--/  filleting
```
