<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cgwgqet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="i-cgwgqet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-2-bold" {...props}></Icon>
