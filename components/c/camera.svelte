<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdi3h-vtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wdi3h-vtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:camera" {...props}></Icon>
