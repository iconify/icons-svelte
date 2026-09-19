<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c772vbbis.css';
import '../../css/l/l6j9zy5iy.css';
import '../../css/p/p2-tfdcvk.css';
import '../../css/g/geakzybqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="c772vbbis"/><path class="l6j9zy5iy"/><path class="p2-tfdcvk"/><path class="geakzybqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:head-side-mask-duo" {...props}></Icon>
