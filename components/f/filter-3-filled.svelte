<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd3xdgnmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="yd3xdgnmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-3-filled" {...props}></Icon>
