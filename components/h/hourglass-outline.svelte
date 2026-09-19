<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc61ku0nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":432};
const content = `<path class="yc61ku0nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hourglass-outline" {...props}></Icon>
