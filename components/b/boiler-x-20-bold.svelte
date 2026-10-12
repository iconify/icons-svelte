<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aazg57bwd.css';
import '../../css/r/r0x1nqbvh.css';
import '../../css/l/l3qindbue.css';
import '../../css/f/fdtytm4ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aazg57bwd"/><path class="r0x1nqbvh"/><path class="l3qindbue"/><path class="fdtytm4ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:boiler-x-20-bold" {...props}></Icon>
