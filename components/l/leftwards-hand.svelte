<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3w5jobuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o3w5jobuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:leftwards-hand" {...props}></Icon>
