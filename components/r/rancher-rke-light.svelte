<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9tfg_yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yu9tfg_yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-rke-light" {...props}></Icon>
