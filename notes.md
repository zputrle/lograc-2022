# Notes

Here you can find general notes on the course Logic in computer science.

## Working in Agda

Types can represents elements:

- data structures,
- mathematical objects,
- propositions, etc.

We can show that a proposition exist by showing there exist a witness, i.e. we show that the type is inhabited. We do that by constructing it.

We are defining new types inductively.

When proving proposition, we often use Proof by induction. This is the same as constructing a recursive function. As Bauer said, induction and recursion are the same thing. They are (probably) the same notion viewed from different contexts.

When constructing a whiteness, we can take advantage of pattern matching and construct witnesses for individual cases.

When constructing a whiteness's (i.e. defining an element/object), the proof assistant can help us:

- We can use hols to ask Agda what type of element we need to construct.
- Agda will simplify types / elements if that is possible. (Probably through computation rules and judgmental equality rules.).
- Then we can use constructors (/ named inference rules) to construct the required element.

constructor = named inference rule
