<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny9vdpbbd.css';
import '../../css/k/ku2rlub5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ny9vdpbbd"/><path class="ku2rlub5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chisel-20" {...props}></Icon>
