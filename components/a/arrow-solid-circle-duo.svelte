<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/h/h2eecabmn.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/h/hg98oub6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="h2eecabmn"/><path class="w4vxnac6h"/><path class="hg98oub6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-circle-duo" {...props}></Icon>
