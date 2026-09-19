<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nr7kg5b3t.css';
import '../../css/q/qxv2_z-lb.css';
import '../../css/e/esm1jccio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nr7kg5b3t"/><path class="qxv2_z-lb"/><path class="esm1jccio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:highlighter-duo" {...props}></Icon>
