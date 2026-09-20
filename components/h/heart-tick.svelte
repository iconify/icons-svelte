<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/ket9b_brq.css';
import '../../css/i/irpq6_opq.css';
import '../../css/n/nu1vehbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ket9b_brq"/><path class="irpq6_opq"/><path class="nu1vehbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:heart-tick" {...props}></Icon>
