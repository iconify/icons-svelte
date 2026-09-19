<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpw-8-bti.css';
import '../../css/y/ydri2mr6x.css';
import '../../css/r/rj1y-5bkj.css';
import '../../css/u/uu14cb_qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="zpw-8-bti"><rect class="ydri2mr6x"/><rect class="rj1y-5bkj"/><rect class="uu14cb_qr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ellipsis-bold" {...props}></Icon>
