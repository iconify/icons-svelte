<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccnad6bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ccnad6bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ferris-wheel" {...props}></Icon>
