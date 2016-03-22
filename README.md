--[[ this plugin is a pre preset color stored--]]
--[[ my gols is all ways make my programming time better and pratical--]]
      --  preset color---
--***************************************************************************************************************************************
input=gma.textinput
cmd=gma.cmd
echo=gma.echo
fb=gma.feedback
level=tonumber(100)
fixture=tonumber(input('what fixture'))
--***************************************************************************************************************************************
fb('my fixture is'..fixture..'and my dimmerlevel is'..level)
echo(fixture..'at'..level)
cmd('attribute"colorrgb1" at 0 ;attribute"colorrgb2" at 0 ;attribute"colorrgb3" at 0')
cmd('store preset 4.1"NC"/m')
fb('NC COLOR HAS BEN STORE ON PRESET 4.1')
end
