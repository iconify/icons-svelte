<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l472vy-ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l472vy-ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mandalorian" {...props}></Icon>
