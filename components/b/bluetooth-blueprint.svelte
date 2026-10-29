<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hngrqwb5t.css';
import '../../css/f/fcyg8zbdc.css';
import '../../css/o/o3ggb2czz.css';
import '../../css/m/mwcb5wb9h.css';
import '../../css/s/saxk-lbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hngrqwb5t wm-deco"/><path class="fcyg8zbdc wm-deco"/><path class="o3ggb2czz wm-deco"/><path class="mwcb5wb9h"/><path class="saxk-lbfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bluetooth-blueprint" {...props}></Icon>
