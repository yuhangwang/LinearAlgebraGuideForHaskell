# Linear Algebra Guide For Haskell
A guide for doing linear algebra in Haskell

(updated: 10/01/2016)

### Recommended packages
* [Eigen](https://hackage.haskell.org/package/eigen)
  Self-contained linear algebra library (Windows friendly)
* [Vec](https://github.com/sedillard/Vec)
  Easy installation on Windows
* [matrix](https://github.com/Daniel-Diaz/matrix)
  (windows friendly)
* [bed-and-breakfast](https://github.com/scravy/bed-and-breakfast)
  pure Haskell (windows friendly)

### Interesting packages
* [numerical](https://github.com/wellposed/numerical)
  not on Hackage yet
* [linear](https://github.com/ekmett/linear/blob/master/linear.cabal)
  more than 10 dependencies


### Packages that are difficult to work with
* [hmatrix](https://github.com/albertoruiz/hmatrix)
  Loading OpenBLAS dll's on windows is easily broken.
  Linking with GSL-LAPACK-BLAS not working on windows.
* [h-cblas](https://github.com/cartazio/hs-cblas)
  too old, ubmaintained (no update for 4~6 years)
* [hs-linear-algebra](https://github.com/patperry/hs-linear-algebra)
  too old, unmaintained (no update for 4~6 years)
