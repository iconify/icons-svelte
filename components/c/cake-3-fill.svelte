<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrlt70_9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlt70_9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cake-3-fill" {...props}></Icon>
