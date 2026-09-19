<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/onyi1eb3m.css';
import '../../css/m/mhz-zfunq.css';
import '../../css/p/pn30itlvh.css';
import '../../css/u/u2a5febix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="onyi1eb3m"/><path class="mhz-zfunq"/><path class="pn30itlvh"/><path class="u2a5febix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:microscope-with-specimen-outline" {...props}></Icon>
