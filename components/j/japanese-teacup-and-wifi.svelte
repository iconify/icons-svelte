<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzyoycbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vzyoycbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:japanese-teacup-and-wifi" {...props}></Icon>
