<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/td8-cml1e.css';
import '../../css/b/bd43g5b1b.css';
import '../../css/i/ijzuod_0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="td8-cml1e"/><path class="bd43g5b1b"/><path class="ijzuod_0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-50-duo" {...props}></Icon>
