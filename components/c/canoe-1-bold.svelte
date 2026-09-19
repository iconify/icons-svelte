<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwk-aybvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uwk-aybvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-1-bold" {...props}></Icon>
