<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ft2r-zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="i-ft2r-zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-valign-center" {...props}></Icon>
