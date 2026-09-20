<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4i0jpbcr.css';
import '../../css/w/w5v8e733c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l4i0jpbcr"/><path class="w5v8e733c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-stat" {...props}></Icon>
