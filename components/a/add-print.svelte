<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/g/g3bzu6tbx.css';
import '../../css/y/y7bupfb4n.css';
import '../../css/f/fm1umgbyy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnjUzDBYM"><g class="hv130ab-t"><path class="g3bzu6tbx"/><path class="y7bupfb4n"/><path class="fm1umgbyy"/></g></mask></defs><path mask="url(#SVGnjUzDBYM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:add-print" {...props}></Icon>
