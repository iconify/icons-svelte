<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9sxgvk4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s9sxgvk4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:incoming-envelope" {...props}></Icon>
