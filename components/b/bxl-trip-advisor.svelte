<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhzb-acko.css';
import '../../css/r/r1ceurbff.css';
import '../../css/z/zsl5jvb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhzb-acko"/><path class="r1ceurbff"/><path class="zsl5jvb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-trip-advisor" {...props}></Icon>
