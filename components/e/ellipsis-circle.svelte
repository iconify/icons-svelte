<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/xonqv8bhq.css';
import '../../css/e/exvi9zkwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="h01tyzbfu"><path class="xonqv8bhq"/><path class="exvi9zkwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ellipsis-circle" {...props}></Icon>
