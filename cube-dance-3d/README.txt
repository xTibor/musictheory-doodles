A better version of Jack Douthett and Peter Steinbach's Cube Dance diagram (1998).

Improvements:
- Cubes are not brutalized anymore.
- Laid out in 3D space instead of that out-of-this-world mess the original diagram used and couldn't wrap my head around.
- Jazz chord symbols.
- Better displays the reflectional and rotational symmetry of the diagram.
- Displays parallel/relative/leading tone chord relations.
- Could be used as a Tonnetz chart alternative.
- Does not require toroidal space or an infinite plane with repeating chords like Tonnetz.

How to use cube-dance-3d-prl2 as a Tonnetz chart alternative

Let's say we want all chords containing the note B. Start with the major B
chord, then apply the following transformations (P/R/L):

- 1st chord: BM
- 2nd chord: P(BM) = Bm
- 3rd chord: L(P(BM)) = L(Bm) = GM
- 4th chord: R(BM) = Abm
- 5th chord: R(L(P(BM))) = R(L(Bm)) = R(GM) = Em
- 6th chord (v1): L(R(BM)) = L(Abm) = EM
- 6th chord (v2): P(R(L(P(BM)))) = P(R(L(Bm))) = P(R(GM)) = P(Em) = EM

So the six chord transformation expressions are:
- Chord,    P(Chord),       L(P(Chord))
- R(Chord), R(L(P(Chord))), L(R(Chord))


