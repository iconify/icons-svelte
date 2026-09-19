<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlest2i5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rlest2i5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:middle-finger" {...props}></Icon>
