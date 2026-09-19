<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1bbnfl8v.css';
import '../../css/l/l_rrpccbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<circle class="z1bbnfl8v"/><path class="l_rrpccbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:chrome" {...props}></Icon>
