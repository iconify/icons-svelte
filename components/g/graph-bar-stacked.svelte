<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlynum9nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlynum9nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-bar-stacked" {...props}></Icon>
