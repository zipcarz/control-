control-
========

...	...	@@ -23,6 +23,7 @@ - (void)viewDidLoad
23	23	     [IMSHandler track:str];
24	24	     NSLog(@"NSString: %@", str);
25	25	    // [IMSHandler wipe:str];
26	+    [IMSHandler untrack:str];
26	27	     [IMSHandler wipeAll];
27	28	     NSLog(@"NSString: %@", str);
28	29	 
