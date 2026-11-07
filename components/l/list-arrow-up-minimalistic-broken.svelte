<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u-zqtib1a.css';
import '../../css/x/xvo0n--hd.css';
import '../../css/h/hjhjwb4fd.css';
import '../../css/u/u_o-z9bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u-zqtib1a"/><path class="xvo0n--hd"/><path class="hjhjwb4fd"/><path class="u_o-z9bwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-up-minimalistic-broken" {...props}></Icon>
