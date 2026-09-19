<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/us3b29bhz.css';
import '../../css/z/zg2y63d-t.css';
import '../../css/m/muicpnbkb.css';
import '../../css/h/hnl-k1btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="us3b29bhz"/><path clip-rule="evenodd" class="zg2y63d-t"/><path class="muicpnbkb"/><path clip-rule="evenodd" class="hnl-k1btp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:camcorder" {...props}></Icon>
