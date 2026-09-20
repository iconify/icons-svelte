<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8-rf8aoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r8-rf8aoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-clip-2" {...props}></Icon>
