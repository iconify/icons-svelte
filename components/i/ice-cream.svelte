<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brwlxwbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="brwlxwbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ice-cream" {...props}></Icon>
