<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/duo8u5b0b.css';
import '../../css/s/s6deurbms.css';
import '../../css/k/kt_jy-ber.css';
import '../../css/p/ptku9_7wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="duo8u5b0b"/><path class="s6deurbms"/><path class="kt_jy-ber"/><path class="ptku9_7wa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-close-linear" {...props}></Icon>
