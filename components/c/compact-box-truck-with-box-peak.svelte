<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh4e6ccdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zh4e6ccdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compact-box-truck-with-box-peak" {...props}></Icon>
