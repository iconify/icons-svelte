<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsv-5w5ym.css';
import '../../css/v/vfhoccbdf.css';
import '../../css/v/vwz4-ew1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hsv-5w5ym"/><path class="vfhoccbdf"/><path class="vwz4-ew1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:building-real-eastate-sign-house-2" {...props}></Icon>
