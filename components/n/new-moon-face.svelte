<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knc_ocbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="knc_ocbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:new-moon-face" {...props}></Icon>
