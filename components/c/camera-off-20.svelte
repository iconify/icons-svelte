<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbi0yub_m.css';
import '../../css/m/msu5rib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pbi0yub_m"/><path class="msu5rib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:camera-off-20" {...props}></Icon>
