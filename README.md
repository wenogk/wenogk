```Swift
struct wenogk {
 func helloWorld() {
  var whatIDo:[String] = ["Native iOS development","Full Stack Development in MongoDB, Express.js, React.js, Node.js"];
  var currentlyWorkingOn = ["A native iOS app that detects your cognitive state based on your speech", "Another native iOS app for a startup company in Dubai"]
  let funFact = "Found a loophole on facebook that allows anyone to send a message as anyone using fake mail headers, when I was 11."
  println("What I do: " + whatIDo.joinWithSeparator(". "))
  println("What I'm currently working on: " + currentlyWorkingOn.joinWithSeparator(". "))
  println("Fun Fact about me: \(funFact)")
 }
}
```
