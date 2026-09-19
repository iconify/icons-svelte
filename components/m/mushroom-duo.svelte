<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m-2eksdvx.css';
import '../../css/j/j53yb7_dq.css';
import '../../css/d/dcx_pp3cp.css';
import '../../css/k/k--9gdclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="m-2eksdvx"/><path class="j53yb7_dq"/><path clip-rule="evenodd" class="dcx_pp3cp"/><path class="k--9gdclz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:mushroom-duo" {...props}></Icon>
