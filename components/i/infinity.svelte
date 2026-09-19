<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysfpi3b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ysfpi3b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:infinity" {...props}></Icon>
