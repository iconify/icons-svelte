<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvhip5cnc.css';
import '../../css/y/y35w4ccky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kvhip5cnc"/><path class="y35w4ccky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-inverter-20" {...props}></Icon>
