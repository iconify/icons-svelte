<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtz7pxbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xtz7pxbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:japanese-castle" {...props}></Icon>
