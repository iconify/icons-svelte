<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sa0bz32lw.css';
import '../../css/x/xslfg2evh.css';
import '../../css/g/g5srfcchm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sa0bz32lw"/><path class="xslfg2evh"/><path class="g5srfcchm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-to-line" {...props}></Icon>
