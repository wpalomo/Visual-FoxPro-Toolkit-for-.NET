# Visual FoxPro Toolkit for .NET
Many years ago someone created a pretty exhaustive .Net Library of FoxPro functions that were identified as nice Fox Stuff to have in .Net. They matched the function names, parameters and return types exactly, as I recall. The source code is available in C# or you can just download the DLL.

I created this repo as a helpful resource in case anyone has a hard time finding it on the web.

Info about it:
  www.codemag.com/article/0209071/The-Visu...Pro-Toolkit-for-.NET 

Download links:
  http://foxcentral.net/microsoft/VFPToolkitNET.htm
  

Here is another helpful resource for VFP developers who want to leaarn about .Net from the perspectinve of their existing FoxPro knowledge:
http://foxcentral.net/microsoft/NETforVFPDevelopers.htm

### Visual FoxPro Toolkit for .NET Team:
- Kamal Patel (Lead Developer, Creator)
- Cathi Gero (Program Manager)
- Rick Hodder (Help)
- Nancy Folsom (Reviewer, Evangelist)
- Ken Levy (Advisor, Communications)


 ## VFPToolkit Namespace:

## Arrays Class
  ### Arrays Members
	ACopy(ref Array aSource, ref Array aDestination)
	ACopy(ref Array aSource, ref Array aDestination, int nFirstSourceElement)
	ACopy(ref Array aSource, ref Array aDestination, int nFirstSourceElement, int nNumberOfSourceElements)
	ACopy(ref Array aSource, ref Array aDestination, int nFirstSourceElement, int nNumberOfSourceElements, int nFirstDestElement)
	ADel(ref Array aArray, int nElementNumber)
	ADel(ref Array aArray, int nElementNumber, int nRemoveColumn)
	ADir(string cFileSkeleton)
	AFont(out string!] aArray)
	AIns(ref Array aArray, int nElementNumber)
	ALen(Array aArray)
	ALen(Array aArray, int nArrayAttribute)
	ALines(out string!) aArray, string cExpression)
	ALines(out string!] aArray, string cExpression, string cParseString)
	APrinters(out string!) aArray)
	AScan(ref Array aArray, object toObject)
	AScan(ref Array aArray, object toObject, int nStartElement)
	AScan(ref Array aArray, object toObject, int nStartElement, int nElementSearched)
	ASort(ref Array aArray)



## Common Class
  ### Common Members
	Empty(string tcString)
	GetPem(object oObject, string cPropertyEventMethodName)
	InList(object toExpression, params object[] toltems)
	IsBlank(bool IValue)
	IsBlank(char IcChar)
	IsBlank(decimal nValue)
	IsBlank(double nValue)
	IsBlank(int nValue)
	IsBlank(long nValue)
	IsBlank(string tcString)
	IsNull(object oObj)
	KeyBoard(string cKey)
	NVL(object oExpl, object oExp2)
	Parameters(MethodBase ms)
	PCount(MethodBase mb)
	RGB(int R, int G, int B)
	Type(object oObj)
	VarType(object oObj)


## Dates Class
### Dates Members
	CDOW(DateTime dDate)
	CMonth(DateTime dDate)
	CTOD(string tcDate)
	CTOT(string cDateTime)
	Date()
	DateTime()
	Day(DateTime dDate)
	DMY(DateTime dDate)
	DOW(DateTime dDate)
	DTOC(DateTime dDate)
	DTOS(DateTime dDate)
	DTOT(DateTimetDateTime)
	GoMonth(DateTime dDate, int nMonths)
	Hour(DateTime dDate)
	MDY(DateTime dDate)
	Minute(DateTime dDate)
	Month(DateTime dDate)
	Quarter(DateTime dDate)
	Sec(DateTime dDate)
	Sec(DateTime dDate)
	Seconds()
	Time()
	TTOC(DateTime dDate)
	TTOD(DateTimetDateTime)
	Week(DateTime tdDate)
	Year(DateTime dDate)


## Dialogs Class
### Dialogs Members
	_GetExtenstion(string IcExtension)
	_GetFile(string tcFilter, int tnFilterIndex, string tcTitle)
	GetColor(Color oColor)
	GetDir()
	GetDir(string tcTitle)
	GetFile()
	GetFile(string tcFileExtension)
	GetFile(string tcFileExtension, string tcTitle)
	GetFont()
	GetFont(Font oFont)
	GetFont(string cFontName, long nFontSize)
	GetPict()
	GetPrinter()
	LocFile(string cFileName)
	MessageBox(string cMessage)
	MessageBox(string cMessage, int nFormat)
	MessageBox(string cMessage, int nFormat, string cTitle)
	PutFile()
	PutFile(string tcTitle)
	PutFile(string tcTitle, string tcFileName)
	PutFile(string tcTitle, string tcFileName, string tcExtension)
	
## Environment Class
### Environment Members
  
	_GetEnv(string IcEnvironmentVariable)
	_ClipText()
	_DbClick()
	CapsLock()
	DiskSpace()
	DiskSpace(string tcDrive)
	DiskSpace(string tcDrive, inttnType)
	DriveType(string tcDrive)
	GetEnv(string cEnvironmentVariable)
	ID()
	InsMode()
	IsMouse()
	NumLock()
	OS()
	PrintStatus()
	PrtInfo()
	sys(int nValue)
	SysMetric(int nValue)
	Version()
	WBorder()
	WBorder(Form toForm)
	WDockable()
	WDockable(Form toForm)
	WFont()
	WFont(Form toForm)
	WMaximum()
	WMaximum(Form toForm)
	WMinimum()
	WMinimum(Form toForm)
	WOnTop(string cWindowCaption)
	WParent()
	WParent(Form toForm)
	WTitle()
	WVisible(string tcWindowCaption)

	
## Files Class
  ### Files Members
	AGetFileVersion(ref string[] aFileInfoArray, string cFileName)
	CurDir()
	DefaultExt(string cFileName, string cExtension)
	Directory(string cPath)
	DisplayPath(string cFileNameWithPath, int nMaxLength)
	FChSize(FileStream oFileStream, int nNewSize)
	FCIose(ref FileStream oFileStream)
	FCreate(string cFileName)
	FDate(string cFileName)
	FEOF(FileStream oFileStream)
	FFIush(FileStream oFileStream)
	File(string cFileName)
	FOpen(string cFileName)
	ForceExt(string cFileName, string cExtension)
	ForcePath(string cFileName, string cPath)
	FPuts(ref FileStream oFileStream, string cString)
	FPuts(ref FileStream oFileStream, string cString, int nCharactersWritten)
	FRead(ref FileStream oFileStream, int nBytes)
	FSeek(ref FileStream oFileStream, int nBytesMoved)
	FSeek(ref FileStream oFileStream, int nBytesMoved, int nRelativePosition)
	FTime(string cFileName)
	FullPath(string cFileName)
	FWrite(ref FileStream oFileStream, string cString)
	FWrite(ref FileStream oFileStream, string cString, int nCharactersWritten)
	Home()
	JustDrive(string cPath)
	JustExt(string cFileName)
	JustFName(string cFileName)
	JustPath(string cPath)
	JustStem(string cPath)


## Help Class
### Help Members
	_Screen()
	CreateObject()
	CreateObjectEx()
	Do()
	DoDefault()
	EditSource()
	GetInterface()
	GetObject()
	IIF()
	NewObject()



## Math Class
### Math Members
	Abs(decimal nNumber)
	Abs(double nNumber)
	Abs(int nNumber)
	ACos(double nNumber)
	ACos(int nNumber)
	ASin(double nNumber)
	ASin(int nNumber)
	ATan(double nNumber)
	ATan(int nNumber)
	Atn2(double nYCoordinate/ double nXCoordinate)
	BitAnd(int tnExpressionl, int tnExpression2)
	BitLShift(int tnExpression, int tnPositions)
	BitNot(int tnExpression)
	BitOr(int tnExpressionl, int tnExpression2)
	BitRShift(int tnExpression, int tnPositions)
	BitTest(int tnExpression, int tnPosition)
	Ceiling(double nNumber)
	Cos(double nNumber)
	Cos(int nNumber)
	DTOR(double nDegrees)
	Exp(double nNumber)
	Floor(double nNumber)
	Int(double nNumber)
	Int(float nNumber)
	Log(decimal nNumber)
	Log(double nNumber)
	Log(int nNumber)
	Log10(decimal nNumber)
	Log10(double nNumber)
	Log10(int nNumber)
	Max(decimal nVaM, decimal nVal2)
	Max(double nVaM, double nVal2)
	Max(float nVaM, float nVal2)
	Max(int nVaM, int nVal2)
	Min(decimal nVaM, decimal nVal2)
	Min(double nVaM, double nVal2)
	Min(float nVaM, float nVal2)


## Strings Class
### Strings Members
	Alltrim(string cExpression)
	Asc(char cCharacter)
	At(string cSearchFor, string cSearchIn)
	At(string cSearchFor, string cSearchIn, int nOccurence)
	AtC(string cSearchFor, string cSearchIn)
	AtC(string cSearchFor, string cSearchIn, int nOccurence)
	AtCLine(string tcSearchExpression, string tcExpressionSearched)
	AtLine(string tcSearchExpression, string tcExpressionSearched)
	Chr(int nAnsiCode)
	ChrTran(string cSearchIn, string cSearchFor, string cReplaceWith)
	CreateBinary(string cExpression)
	FileToStr(string cFileName)
	GetWordCount(string cString)
	GetWordNumb(string cString, int nWordPosition)
	IsAlpha(string cExpression)
	IsDigit(string tcString)
	IsLower(string cExpression)
	IsUpper(string cExpression)
	Left(string cExpression, int nDigits)
	Len(string cExpression)
	Lower(string cExpression)
	LTrim(string cExpression)
	MemLines(string tcString)
	MLine(string tcString, inttnLineNo)
	Occurs(chartcChar, string cExpression)
	Occurs(string cString, string cExpression)
	PadC(string cExpression, int nResultSize)
	PadC(string cExpression, int nResultSize, char cPaddingChar)
	PadL(string cExpression, int nResultSize)
	PadL(string cExpression, int nResultSize, char cPaddingChar)
	PadR(string cExpression, int nResultSize)
	PadR(string cExpression, int nResultSize, char cPaddingChar)
	Proper(string cString)
	Rat(string cSearchFor, string cSearchIn)
	Rat(string cSearchFor, string cSearchIn, int nOccurence)
	RatLine(string tcSearchExpression, string tcExpressionSearched)
	Replicate(string cExpression, int nTimes)
	Right(string cExpression, int nDigits)
	RTrim(string cExpression)
	Space(int nSpaces)
	Str(decimal nNumber)
	Str(double nNumber)
	Str(int nNumber)
	StrExtract(string cSearchExpression, string cBeginDelim)
	StrExtract(string cSearchExpression, string cBeginDelim, string cEndDelim)
	StrExtract(string cSearchExpression, string cBeginDelim, string cEndDelim, int nBeginOccurence)
	StrExtract(string cSearchExpression, string cBeginDelim, string cEndDelim, int nBeginOccurence, int nFlags)
	StrToFile(string cExpression, string cFileName)
	StrToFile(string cExpression, string cFileName, bool lAdditive)
	StrTran(string cSearchIn, string cSearchFor)
	StrTran(string cSearchIn, string cSearchFor, string cReplaceWith)
	StrTran(string cSearchIn, string cSearchFor, string cReplaceWith, int nStartoccurence, int nCount)
	Stuff(string cExpression, int nStartReplacement, int nCharactersReplaced, string cReplacement)
	SubStr(string cExpression, int nStartPosition)
	SubStr(string cExpression, int nStartPosition, int nLength)
	Trim(string cExpression)
	Upper(string cExpression)
	Val(string cExpression)


## VfpData Class
### vfpData Members
	_Filter
	_Found
	_Order
	Alias()
	AppendBlank()
	AppendBlank(DataView toView)
	BOF(int nRowNumber)
	BOF(int nRowNumber, DataView toView)
	Browse()
	Browse(DataView toView)
	Count()
	Count(DataView toView)
	Count(string tcFilterCondition)
	Count(string tcFilterCondition, DataView toView)
	CursorToXML(DataSettoDataSet, string tcFileName)
	CurVal(string tcField, DataRowtoRow)
	Delete(int nRecNo)
	Delete(int nRecNo, DataView toView)
	DeleteAll()
	DeleteAII(DataView toView)
	Deleted(int nRecNo)	
	Deleted(int nRecNo, DataView toView)	
	DeleteFor(string cExpression)	
	DeleteFor(string cExpression, DataView toView)	
	Descending()
	Descending(DataView toView)	
	EOF(int nRowNumber)	
	EOF(int nRowNumber, DataView toView)	
	FCount()
	FCount(DataView toView)	
	Field(int nPosition)	
	Field(int nPosition, DataView toView)	
	Filter()
	Filter(DataView toView)	
	Found()
	IndexSeek(string tcExpression)	
	IndexSeek(string tcExpression, DataView toView)	
	IsReadOnly()
	IsReadOnly(DataView toView)
	Lookup(string tcReturnField, string tcSearchExpression, string tcSearchedField)
	Lookup(string tcReturnField, string tcSearchExpression, string tcSearchedField, DataView toView)
	Order()
	Order(DataView toView)
	oView
	Recall(int nRecNo)
	Recall(int nRecNo, DataView toView)
	RecCount()
	RecCount(DataView toView)
	Seek(string tcString)
	Seek(string tcString, DataView toView)
	Select(DataView toView)
	Set(string tcCommandType)
	SetFilterTo(string tcFilterExpression)
	SetFilterTo(string tcFilterExpression, DataView toView)
	SetOrderTo(string tcFieldName)
	SetOrderTo(string tcFieldName, DataView toView)
	SqlConnect(string tcConnectionString)
	SqlDisConnect(OleDbConnection toConn)
	SqlExecute(OleDbConnection toConn, OleDbCommand toCommand)
	SqlExecute(OleDbConnection toConn, OleDbCommand toCommand, string tcAlias)
	SqlExecute(OleDbConnection toConn, string tcSQL)
	SqlExecute(OleDbConnection toConn, string tcSQL, string tcAlias)
	SqlStringConnect(string tcConnectionString)
	XMLToCursor(string tcFileName, string tcDataSet)


