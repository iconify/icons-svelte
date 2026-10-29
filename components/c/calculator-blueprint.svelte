<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/ixx_sebyw.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/f/f8h9mitoo.css';
import '../../css/n/nh5rovrci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ixx_sebyw wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="f8h9mitoo wm-k"/><path class="nh5rovrci wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calculator-blueprint" {...props}></Icon>
