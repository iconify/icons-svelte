<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sbg5d4pwg.css';
import '../../css/u/uhc_l5zqc.css';
import '../../css/s/sse0u-xjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sbg5d4pwg"/><path class="uhc_l5zqc"/><path class="sse0u-xjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:qr-duo" {...props}></Icon>
