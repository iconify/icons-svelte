<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa6bx_bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fa6bx_bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:atom" {...props}></Icon>
