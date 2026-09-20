<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/pcl3d89qc.css';
import '../../css/l/la7gkwdbc.css';
import '../../css/n/nv0xecb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pcl3d89qc"/><path class="la7gkwdbc"/><path class="nv0xecb8e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headset-off-sharp-two-tone" {...props}></Icon>
