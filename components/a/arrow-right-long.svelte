<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woxg0sbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="woxg0sbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-right-long" {...props}></Icon>
