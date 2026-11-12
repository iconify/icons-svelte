<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8mo5s6gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8mo5s6gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeresend-dark" {...props}></Icon>
