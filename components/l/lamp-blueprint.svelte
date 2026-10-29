<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/op1sfgeen.css';
import '../../css/v/vja3av1ob.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/b/btbdntbyc.css';
import '../../css/e/ewwv0nb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="op1sfgeen wm-deco"/><path class="vja3av1ob wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="btbdntbyc"/><path class="ewwv0nb-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lamp-blueprint" {...props}></Icon>
