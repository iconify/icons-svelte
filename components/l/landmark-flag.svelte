<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wssrv4thr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wssrv4thr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:landmark-flag" {...props}></Icon>
