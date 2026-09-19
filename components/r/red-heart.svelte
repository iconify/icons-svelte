<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_-vhbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ri_-vhbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:red-heart" {...props}></Icon>
