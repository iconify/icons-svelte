<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kp4sgbfpe.css';
import '../../css/i/iqamq8bdl.css';
import '../../css/y/y6ovjwbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kp4sgbfpe"/><path class="iqamq8bdl"/><path class="y6ovjwbid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:moon-landing" {...props}></Icon>
