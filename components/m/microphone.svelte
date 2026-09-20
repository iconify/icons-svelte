<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmv64kb3y.css';
import '../../css/i/i0y_0bc6h.css';
import '../../css/k/kzdoctbde.css';
import '../../css/m/m8r8jhb2o.css';
import '../../css/z/zb05pv2-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cmv64kb3y"/><path class="i0y_0bc6h"/><path class="kzdoctbde"/><path class="m8r8jhb2o"/><path class="zb05pv2-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:microphone" {...props}></Icon>
