<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqjo_17sw.css';
import '../../css/f/fv344tbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqjo_17sw"/><path class="fv344tbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-inverter-20-bold" {...props}></Icon>
