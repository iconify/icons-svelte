<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wah-fvb3g.css';
import '../../css/r/r_s45d2gs.css';
import '../../css/u/utnhp4bhf.css';
import '../../css/l/lqpy27syi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wah-fvb3g"/><path class="r_s45d2gs"/><path class="utnhp4bhf"/><rect class="lqpy27syi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-pills-linear" {...props}></Icon>
