<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yhv5abczy.css';
import '../../css/r/rppt24xri.css';
import '../../css/d/dno4_nblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yhv5abczy"/><path class="rppt24xri"/><path class="dno4_nblm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cast-sharp-two-tone" {...props}></Icon>
