#CS 541 Wiki
Post any pitfalls and solutions here.

One thing to notice is that many other references call the Database "DB" class what is called DiskMgr for our implementation. So for the implementation below they use a DB class but for that we will use DiskMgr and will be able to use the same methods.

[Nice reference for buffer manager](http://buffermanager.eclipselabs.org.codespot.com/svn-history/r22/src/bufmgr/BufMgr.java)

Many other examples use a wrapper of this DB class called JavabaseDB. So very confusing terminology but this is how the Javabase is wrapped up if we need it to understand other implementations that use this abstraction.

[To understand Javabase in other examples](http://bd-cuneiforme.googlecode.com/svn/trunk/src/MINIBASE/global/SystemDefs.java)




