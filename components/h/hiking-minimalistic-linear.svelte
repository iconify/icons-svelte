<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/einr_36wa.css';
import '../../css/r/ry6ouwbrz.css';
import '../../css/n/nxfzdyb0n.css';
import '../../css/a/aji3_8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="einr_36wa"/><path class="ry6ouwbrz"/><path class="nxfzdyb0n"/><path class="aji3_8bki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hiking-minimalistic-linear" {...props}></Icon>
