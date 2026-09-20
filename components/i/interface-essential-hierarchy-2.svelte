<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3m4t9b0x.css';
import '../../css/j/j55bh1bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d3m4t9b0x"/><path class="j55bh1bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-hierarchy-2" {...props}></Icon>
