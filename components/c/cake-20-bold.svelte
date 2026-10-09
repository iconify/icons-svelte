<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua393o__d.css';
import '../../css/p/pi73q5bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ua393o__d"/><path class="pi73q5bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cake-20-bold" {...props}></Icon>
