<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hxlk_nblr.css';
import '../../css/s/sr6e6_bvi.css';
import '../../css/k/ktcv0ybny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hxlk_nblr"/><path class="sr6e6_bvi"/><path class="ktcv0ybny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:eye-1-slash-duo" {...props}></Icon>
