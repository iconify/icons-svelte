<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry77vccoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ry77vccoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:office-building" {...props}></Icon>
