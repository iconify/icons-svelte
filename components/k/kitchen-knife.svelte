<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0tfrccvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j0tfrccvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:kitchen-knife" {...props}></Icon>
