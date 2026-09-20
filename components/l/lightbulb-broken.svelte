<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uw6indbog.css';
import '../../css/x/xvqdltb2j.css';
import '../../css/x/x8z4k_bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uw6indbog"/><path class="xvqdltb2j"/><path class="x8z4k_bji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-broken" {...props}></Icon>
