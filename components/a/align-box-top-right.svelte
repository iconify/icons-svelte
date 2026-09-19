<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p01z6lbzt.css';
import '../../css/y/yj2dzvo6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="yj2dzvo6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:align-box-top-right" {...props}></Icon>
