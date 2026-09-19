<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ruunz1mfm.css';
import '../../css/n/n4d1ysgow.css';
import '../../css/s/sis5cgh5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ruunz1mfm"/><path class="n4d1ysgow"/><path class="sis5cgh5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camcorder-duo" {...props}></Icon>
