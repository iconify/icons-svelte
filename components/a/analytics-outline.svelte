<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y1t264bjm.css';
import '../../css/r/r-o9b9btm.css';
import '../../css/w/ws_4u_45s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="y1t264bjm"/><path clip-rule="evenodd" class="r-o9b9btm"/><path class="ws_4u_45s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:analytics-outline" {...props}></Icon>
