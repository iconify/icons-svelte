<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/i/im8wmac8f.css';
import '../../css/z/zr5m9kbwl.css';
import '../../css/z/z3w9o1b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="im8wmac8f"/><path class="zr5m9kbwl"/><path class="z3w9o1b2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-trending-up-sparkles-sharp-duotone" {...props}></Icon>
