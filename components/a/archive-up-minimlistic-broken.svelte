<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l-llhz78d.css';
import '../../css/t/t6vi4ublf.css';
import '../../css/n/nxeolsbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l-llhz78d"/><path class="t6vi4ublf"/><path class="nxeolsbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-up-minimlistic-broken" {...props}></Icon>
