<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-lx775bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="f-lx775bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:magnet-bold" {...props}></Icon>
