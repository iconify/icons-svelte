<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrq7_2bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yrq7_2bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:cursor-arrow" {...props}></Icon>
