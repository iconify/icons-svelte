<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx_o-7mra.css';
import '../../css/x/xonpjubig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hx_o-7mra"/><path class="xonpjubig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-boat-20-bold" {...props}></Icon>
