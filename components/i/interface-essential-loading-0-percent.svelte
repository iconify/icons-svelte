<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi-r0bcdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pi-r0bcdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-0-percent" {...props}></Icon>
