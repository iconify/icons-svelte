<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nftd1kjvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nftd1kjvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-square" {...props}></Icon>
