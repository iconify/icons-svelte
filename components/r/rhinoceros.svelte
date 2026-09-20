<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip3_c083h.css';
import '../../css/y/ymnh5s7qn.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/d-a-ltu6p.css';
import '../../css/q/qtmnxsb0t.css';
import '../../css/t/tmj_9mbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ip3_c083h"/><path class="ymnh5s7qn"/><g class="ij2x_72vy"><path class="d-a-ltu6p"/><path class="qtmnxsb0t"/><path class="tmj_9mbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:rhinoceros" {...props}></Icon>
