<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwke6u-sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vwke6u-sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ring-linked-to-ring-with-jewel" {...props}></Icon>
