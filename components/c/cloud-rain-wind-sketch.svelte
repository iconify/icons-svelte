<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d4nyqcchx.css';
import '../../css/w/wa2lq1bmf.css';
import '../../css/j/jje4tjgwk.css';
import '../../css/d/dluc55baa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d4nyqcchx"/><path class="wa2lq1bmf wm-a"/><path class="jje4tjgwk wm-k"/><path class="dluc55baa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-rain-wind-sketch" {...props}></Icon>
