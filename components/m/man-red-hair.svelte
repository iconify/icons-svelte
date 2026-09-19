<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zafgt3y5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="zafgt3y5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:man-red-hair" {...props}></Icon>
