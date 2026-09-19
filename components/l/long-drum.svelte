<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-1_1ma1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w-1_1ma1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:long-drum" {...props}></Icon>
