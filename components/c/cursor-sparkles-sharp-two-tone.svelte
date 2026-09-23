<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/s/sf41u5dyp.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/z/z3w9o1b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sf41u5dyp"/><path class="zr5m9kbwl"/><path class="z3w9o1b2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-sparkles-sharp-two-tone" {...props}></Icon>
