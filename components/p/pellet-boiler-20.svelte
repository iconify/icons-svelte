<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxjtvuboi.css';
import '../../css/p/pzrdwd7sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mxjtvuboi"/><path class="pzrdwd7sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pellet-boiler-20" {...props}></Icon>
