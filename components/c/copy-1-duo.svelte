<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xu2hubcwa.css';
import '../../css/f/fc-f16bov.css';
import '../../css/u/u_2b3msej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xu2hubcwa"/><path class="fc-f16bov"/><path class="u_2b3msej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:copy-1-duo" {...props}></Icon>
