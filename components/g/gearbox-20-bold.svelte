<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncnjsrrtg.css';
import '../../css/m/mo1ard8kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncnjsrrtg"/><path class="mo1ard8kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gearbox-20-bold" {...props}></Icon>
