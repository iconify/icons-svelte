<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/v/vd9kimbsu.css';
import '../../css/r/r0e2nujzx.css';
import '../../css/s/sdaucgb_l.css';
import '../../css/s/sumcvejxs.css';
import '../../css/v/vr57sgb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="vd9kimbsu wm-deco"/><path class="r0e2nujzx wm-deco"/><path class="sdaucgb_l wm-deco"/><path class="sumcvejxs"/><path class="vr57sgb0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplet-blueprint" {...props}></Icon>
