<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ih2r9krfu.css';
import '../../css/m/mkwvu5bez.css';
import '../../css/g/gweihee3d.css';
import '../../css/u/ujrmgmblc.css';
import '../../css/o/obcs1cbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ih2r9krfu"/><path class="mkwvu5bez"/><path class="gweihee3d"/><path class="ujrmgmblc"/><path class="obcs1cbgf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:microphone-linear" {...props}></Icon>
