<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef1_z1bld.css';
import '../../css/h/h0_g0cb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef1_z1bld"/><path class="h0_g0cb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-car-garage" {...props}></Icon>
