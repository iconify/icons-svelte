<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x95pl0b1p.css';
import '../../css/k/kby29y5kq.css';
import '../../css/h/h8cf16owo.css';
import '../../css/f/f_v564bkt.css';
import '../../css/t/tm5d6wbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="x95pl0b1p"/><path class="kby29y5kq"/><rect class="h8cf16owo"/><path class="f_v564bkt"/><path class="tm5d6wbua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:copy-2" {...props}></Icon>
