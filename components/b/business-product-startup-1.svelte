<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn8-qiy_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rn8-qiy_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:business-product-startup-1" {...props}></Icon>
