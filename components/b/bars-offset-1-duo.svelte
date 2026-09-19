<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfw55jhmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vfw55jhmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-1-duo" {...props}></Icon>
