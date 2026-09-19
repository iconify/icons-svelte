<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vtcmcgchf.css';
import '../../css/g/gnio0ig7m.css';
import '../../css/s/scnmdvh_t.css';
import '../../css/o/ohrf1znlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vtcmcgchf"/><path class="gnio0ig7m"/><path class="scnmdvh_t"/><path class="ohrf1znlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:multi-mac-os-window" {...props}></Icon>
