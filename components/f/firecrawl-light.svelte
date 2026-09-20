<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yun3io12r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yun3io12r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firecrawl-light" {...props}></Icon>
