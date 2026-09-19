<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq6rgdxdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tq6rgdxdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:nine-of-circles-mahjong-filled" {...props}></Icon>
