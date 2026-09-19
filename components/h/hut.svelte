<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ha0-b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j7ha0-b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:hut" {...props}></Icon>
