<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kh3iwjkha.css';
import '../../css/r/r5hrfmbxe.css';
import '../../css/y/yjks-vsfu.css';
import '../../css/r/r14ix6krv.css';
import '../../css/v/vn8ld76mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kh3iwjkha"/><path class="r5hrfmbxe"/><path clip-rule="evenodd" class="yjks-vsfu"/><path class="r14ix6krv"/><path class="vn8ld76mb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:eye-1" {...props}></Icon>
