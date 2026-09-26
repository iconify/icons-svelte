<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yc1eq-awn.css';
import '../../css/v/vbwan82rd.css';
import '../../css/a/alf7g0r-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yc1eq-awn"/><path class="vbwan82rd"/><path class="alf7g0r-x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-left-open-line-duotone" {...props}></Icon>
