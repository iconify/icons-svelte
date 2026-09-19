<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmdx1rbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dmdx1rbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-kiss-wink-heart" {...props}></Icon>
