<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8x1_xoez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l8x1_xoez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-harness-on-leash" {...props}></Icon>
