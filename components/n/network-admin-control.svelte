<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-4i3u_dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j-4i3u_dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-admin-control" {...props}></Icon>
