<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3anlkbiz.css';
import '../../css/k/kemupybsm.css';
import '../../css/a/add8lcush.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m3anlkbiz"/><path class="kemupybsm"/><path class="add8lcush"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inspection-20" {...props}></Icon>
