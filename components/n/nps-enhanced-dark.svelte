<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw_f9jbmc.css';
import '../../css/f/f1xyaebmo.css';
import '../../css/m/m2qk5o2nd.css';
import '../../css/c/crbo13bgz.css';
import '../../css/d/dy_nph56k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dw_f9jbmc"/><path class="f1xyaebmo"/><path class="m2qk5o2nd"/><path class="crbo13bgz"/><path class="dy_nph56k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nps-enhanced-dark" {...props}></Icon>
