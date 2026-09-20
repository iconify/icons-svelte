<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sk1228b2x.css';
import '../../css/e/ezshh0bgn.css';
import '../../css/l/lum82dbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sk1228b2x"/><path class="ezshh0bgn"/><path class="lum82dbar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exit-line-duotone" {...props}></Icon>
