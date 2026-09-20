<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zchtgcboh.css';
import '../../css/i/i1-lcibyb.css';
import '../../css/i/i5-w2mb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zchtgcboh"/><path class="i1-lcibyb"/><path class="i5-w2mb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-print" {...props}></Icon>
