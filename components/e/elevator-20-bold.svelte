<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev30ibc3d.css';
import '../../css/d/dlfk2kx2y.css';
import '../../css/f/feh6r_b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ev30ibc3d"/><path class="dlfk2kx2y"/><path class="feh6r_b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:elevator-20-bold" {...props}></Icon>
