<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agxl_l40w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agxl_l40w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-share-3" {...props}></Icon>
