<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ivimbut.css';
import '../../css/n/ne1liqbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o3ivimbut"/><path class="ne1liqbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-horizontal-20" {...props}></Icon>
