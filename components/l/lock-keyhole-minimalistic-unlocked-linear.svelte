<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mgx0gjb2o.css';
import '../../css/p/pdyvfubiy.css';
import '../../css/d/d_tqh4qme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mgx0gjb2o"/><path class="pdyvfubiy"/><path class="d_tqh4qme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-keyhole-minimalistic-unlocked-linear" {...props}></Icon>
