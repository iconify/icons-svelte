<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7nqu2bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i7nqu2bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:boomerang" {...props}></Icon>
