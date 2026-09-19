<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hxgyvsbny.css';
import '../../css/e/exvi9zkwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="h01tyzbfu"><path class="hxgyvsbny"/><path class="exvi9zkwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ellipsis-square" {...props}></Icon>
