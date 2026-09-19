<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps0ot-_-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ps0ot-_-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:drop-of-blood" {...props}></Icon>
