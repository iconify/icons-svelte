<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzsphib5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vzsphib5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:crossed-swords" {...props}></Icon>
