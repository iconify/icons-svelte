<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyq7z9z1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xyq7z9z1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:raised-back-of-hand" {...props}></Icon>
