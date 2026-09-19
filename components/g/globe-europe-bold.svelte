<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bpin_ybto.css';
import '../../css/g/gfb8_jren.css';
import '../../css/d/dtjzbs3_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bpin_ybto"/><path clip-rule="evenodd" class="gfb8_jren"/><path class="dtjzbs3_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-europe-bold" {...props}></Icon>
