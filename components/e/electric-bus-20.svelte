<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2_zy01_l.css';
import '../../css/u/uvhzmp04b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r2_zy01_l"/><path class="uvhzmp04b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-bus-20" {...props}></Icon>
