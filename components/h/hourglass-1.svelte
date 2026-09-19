<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rp6538qpk.css';
import '../../css/a/aqdcgn30f.css';
import '../../css/e/eve4-3bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rp6538qpk"/><path class="aqdcgn30f"/><path clip-rule="evenodd" class="eve4-3bhx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hourglass-1" {...props}></Icon>
