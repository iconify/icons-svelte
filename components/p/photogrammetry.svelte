<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a44nu1b1v.css';
import '../../css/p/pdt_z-fvk.css';
import '../../css/f/fx90jorko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a44nu1b1v"/><path class="pdt_z-fvk"/><path class="fx90jorko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:photogrammetry" {...props}></Icon>
