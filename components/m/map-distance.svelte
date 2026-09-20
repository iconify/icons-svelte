<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ffnnpya0h.css';
import '../../css/u/ug2jtujvf.css';
import '../../css/q/qlvm9bbto.css';
import '../../css/t/tc4eo1bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ffnnpya0h"/><path class="ug2jtujvf"/><path class="qlvm9bbto"/><path class="tc4eo1bjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-distance" {...props}></Icon>
