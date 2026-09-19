<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg51_9s6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1536};
const content = `<path class="yg51_9s6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:print" {...props}></Icon>
