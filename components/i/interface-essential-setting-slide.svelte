<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk4zobbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rk4zobbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-setting-slide" {...props}></Icon>
