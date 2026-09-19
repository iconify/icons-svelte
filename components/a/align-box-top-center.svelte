<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p01z6lbzt.css';
import '../../css/x/xp7skg3_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p01z6lbzt"/><path class="xp7skg3_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:align-box-top-center" {...props}></Icon>
