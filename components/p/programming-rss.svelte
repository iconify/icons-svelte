<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz2p-gb2y.css';
import '../../css/q/qlm8aybxt.css';
import '../../css/l/l8l993bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uz2p-gb2y"/><path class="qlm8aybxt"/><path class="l8l993bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:programming-rss" {...props}></Icon>
