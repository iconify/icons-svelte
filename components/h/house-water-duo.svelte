<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i793flwcp.css';
import '../../css/m/m5_x9zgtq.css';
import '../../css/k/kaec_pgza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i793flwcp"/><path class="m5_x9zgtq"/><path class="kaec_pgza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-water-duo" {...props}></Icon>
