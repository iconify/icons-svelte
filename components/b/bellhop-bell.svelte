<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf_p6lzmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vf_p6lzmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bellhop-bell" {...props}></Icon>
