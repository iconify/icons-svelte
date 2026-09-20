<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeoy3pben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yeoy3pben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pin-cancelled" {...props}></Icon>
