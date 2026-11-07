<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qpizk3b2i.css';
import '../../css/k/krvkaiboe.css';
import '../../css/y/ytwl2ebtc.css';
import '../../css/r/rmwzjebkv.css';
import '../../css/o/ou-u7bcws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qpizk3b2i"/><path class="krvkaiboe"/><path class="ytwl2ebtc"/><path class="rmwzjebkv"/><path class="ou-u7bcws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-add-linear" {...props}></Icon>
