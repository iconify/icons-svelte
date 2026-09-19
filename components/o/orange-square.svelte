<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2rvh9ety.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u2rvh9ety"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:orange-square" {...props}></Icon>
