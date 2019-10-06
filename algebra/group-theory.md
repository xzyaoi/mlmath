---
description: Group is a set with operation.
---

# Group Theory

## Definitions and Properties

**Definition 2.1.1 \(Definition of Group\)** Let $$G$$ be a set and " $$\star$$ " an operation, i.e. an application defined from $$G \times D$$ onto G:

$$
\forall (x,y) \in G \times G, x \star y \in G
$$

that has the following properties:

1. $$\forall x,y,z \in G, (x \star y) \star z = x \star (y \star z)$$:$$\star$$ is associative.
2. $$\exists e \in G, \forall x \in G, x \star e = e \star x = x$$: e is a neutral element, also called identity, unity.
3. $$\forall x \in G, \exists y \in G, x \star y = y \star x = e$$: y is an inverse of $$x$$.

is called a group.

**Definition 2.1.2 \(Definition of Abelian/Commutative Group\)** 

If $$G$$ is a group, and $$\forall x, y \in G, x \star y = y \star x$$**,** then the group $$G$$ is said to be commutative or Abelian. _The name Abelian group is a salute to a Norwegian mathematician named_ [_Niels Henrik Abel_](https://en.wikipedia.org/wiki/Niels_Henrik_Abel)_._

**Properties 2.1.3 \(Properties of Group\) Proof**

1. The neutral element is unique.
2. Inverse of ****$$x$$ is unique. 
3. Let $$a,b \in G$$, there exists a unique $$x \in G$$ such that $$a \star x = b$$, this is $$x = a^{-1} \star b$$.

## Morphism

**Definition 2.2.1 \(Definition of Group Morphism\)** 

Let$$(G, \star)$$ and$$(F, \bullet)$$ two groups. An application $$f: G \rightarrow F$$ is called a group morphism if $$\forall x,y \in G$$, $$f(x \star y) = f(x) \bullet f(y)$$.

**Properties 2.2.2 \(Properties of Group Morphism\)**

1. If $$e$$ is the neutral element in $$G$$ and $$e'$$ is the neutral element of $$F$$, then $$f(e) =e'$$.
2. $$\forall x \in G, f(x^{-1}) = (f(x))^{-1}$$ .
3. $$\forall x \in G, n \in \mathbb{Z}, f(x^{n})=(f(x))^{n}$$.





## Product of Groups

## Subgroups, Properties of Subgroup

## Other Properties of groups

## Distinguished Groups

## Quotient Groups

## Symmetric Group

