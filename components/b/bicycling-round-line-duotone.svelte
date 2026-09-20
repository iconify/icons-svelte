<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mrtq9bbsf.css';
import '../../css/v/vu97hgmrr.css';
import '../../css/y/ym7z_obxz.css';
import '../../css/n/nuz684-gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="mrtq9bbsf"/><circle class="vu97hgmrr"/><circle class="ym7z_obxz"/><path class="nuz684-gh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bicycling-round-line-duotone" {...props}></Icon>
