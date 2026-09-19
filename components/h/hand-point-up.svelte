<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssduk0_dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ssduk0_dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-point-up" {...props}></Icon>
