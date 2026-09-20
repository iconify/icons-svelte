<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y94hyzjei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y94hyzjei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-cursor-click-point" {...props}></Icon>
