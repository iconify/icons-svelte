<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prssdsbsb.css';
import '../../css/p/p90oggben.css';
import '../../css/i/i59ju7bdr.css';
import '../../css/y/y77ro9r-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prssdsbsb"/><path class="p90oggben"/><path class="i59ju7bdr"/><path class="y77ro9r-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-station-20-bold" {...props}></Icon>
