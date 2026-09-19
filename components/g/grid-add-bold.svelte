<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/p/phbwvobjr.css';
import '../../css/f/fnpl309tr.css';
import '../../css/j/jcvlxyb4x.css';
import '../../css/c/ce1wgkbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="pr52f_b5y"><rect class="phbwvobjr"/><rect class="fnpl309tr"/><rect class="jcvlxyb4x"/><path class="ce1wgkbld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-add-bold" {...props}></Icon>
