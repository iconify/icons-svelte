<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfjg_pboc.css';
import '../../css/x/xmtv_m_5x.css';
import '../../css/g/gy5agkitl.css';
import '../../css/e/etm4r5s3x.css';
import '../../css/q/q90ux4a1y.css';
import '../../css/k/kyb7ylb4r.css';
import '../../css/j/jdyfkwtit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfjg_pboc"/><path class="xmtv_m_5x"/><path class="gy5agkitl"/><path class="etm4r5s3x"/><path class="q90ux4a1y"/><path class="kyb7ylb4r"/><path class="jdyfkwtit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-bold-duotone" {...props}></Icon>
