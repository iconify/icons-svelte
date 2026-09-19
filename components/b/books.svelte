<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veu3tfbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="veu3tfbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:books" {...props}></Icon>
