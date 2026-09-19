<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh2_1rb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sh2_1rb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bone" {...props}></Icon>
