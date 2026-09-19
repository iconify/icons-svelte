<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykhb4xi8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ykhb4xi8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:ringed-planet" {...props}></Icon>
