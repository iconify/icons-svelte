<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0zgyobhy.css';
import '../../css/s/su9vssb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0zgyobhy"/><path class="su9vssb1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:kg-1x1" {...props}></Icon>
