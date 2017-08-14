# Resource:
## [Growing Object Oriented Software Guided By Tests](http://www.cs.umss.edu.bo/doc/material/mat_gral_137/Addison.Wesley.Growing.Object.Oriented.Software.Guided.by.Tests.Oct.2009%20(1).pdf)

# Chapter 7 Notes

* It is important to define the right boundaries of objects so that it plays well with it's neighbors.
* Three aspects of TDD help to achieve this:
	1. Forces to describe *what* before *how.*
	2. To keep tests understandable we have to limit their scope.
	3. To construct a test we must understand an objects dependencies.
* Value types - It helps to define types to represent value concepts in the domain.
	* For example defining and Item type instead of using a String.
* Three techniques for creating value types:
	1. Breaking out
		* Break up an object if it becomes to difficult to test or the test failures are too difficult to test.
	2. Budding off
	3. Bundling up
* I don't understand the the purpose of the two examples in the section "Compose Objects to Describe System Behavior"

# Chapter 8 Notes

* What is an adapter layer? What is an example of an adapter layer?
	* We should mock code we don't own (i.e. libraries). Does this layer return instances of things that our code might depend on?
