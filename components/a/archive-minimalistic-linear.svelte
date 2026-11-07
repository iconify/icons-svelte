<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wqs3cnbmu.css';
import '../../css/i/iscitzuxy.css';
import '../../css/r/rj_fhqb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wqs3cnbmu"/><path class="iscitzuxy"/><path class="rj_fhqb-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-minimalistic-linear" {...props}></Icon>
