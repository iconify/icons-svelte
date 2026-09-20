<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/walr4d8bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="walr4d8bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-burger-on-bun-with-seeds" {...props}></Icon>
