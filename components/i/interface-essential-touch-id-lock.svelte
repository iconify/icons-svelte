<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1lqv4b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k1lqv4b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-touch-id-lock" {...props}></Icon>
