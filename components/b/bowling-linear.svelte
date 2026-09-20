<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/h/hhov-gbog.css';
import '../../css/d/dcgw77bis.css';
import '../../css/s/soqsp2xkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="shu3xdl9q"/><circle transform="rotate(-90 12 7)" class="hhov-gbog"/><circle transform="rotate(-90 12 12)" class="dcgw77bis"/><path class="soqsp2xkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bowling-linear" {...props}></Icon>
