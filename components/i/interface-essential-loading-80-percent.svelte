<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll91ww2cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ll91ww2cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-80-percent" {...props}></Icon>
