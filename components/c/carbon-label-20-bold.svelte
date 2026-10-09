<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rul6h_x9m.css';
import '../../css/h/hgjw24b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rul6h_x9m"/><path class="hgjw24b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-label-20-bold" {...props}></Icon>
