<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmgp-hp4m.css';
import '../../css/y/ylee2db2d.css';
import '../../css/a/ay1aj8o0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmgp-hp4m"/><path class="ylee2db2d"/><path class="ay1aj8o0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-meter-20-bold" {...props}></Icon>
