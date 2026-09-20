<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov0lzdbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ov0lzdbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badge-shield-with-exclamation-point" {...props}></Icon>
