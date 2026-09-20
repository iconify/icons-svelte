<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/srz1_-b8a.css';
import '../../css/n/nt3sg5wfu.css';
import '../../css/k/kklqr_b8v.css';
import '../../css/s/stn1gcc8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="srz1_-b8a"/><path class="nt3sg5wfu"/><path class="kklqr_b8v"/><path class="stn1gcc8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plate-outline" {...props}></Icon>
