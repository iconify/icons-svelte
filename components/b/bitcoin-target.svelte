<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/syqwyou8e.css';
import '../../css/k/kvzo1egcq.css';
import '../../css/i/iycsllbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="syqwyou8e"/><path class="kvzo1egcq"/><path class="iycsllbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-target" {...props}></Icon>
