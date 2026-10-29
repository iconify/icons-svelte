<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf5rlnb_s.css';
import '../../css/r/ro5v85bqf.css';
import '../../css/l/lnysw87pu.css';
import '../../css/c/cxeqomklq.css';
import '../../css/h/h_xsybc4i.css';
import '../../css/u/uu_mg3b0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf5rlnb_s wm-shadow"/><path class="ro5v85bqf wm-k"/><path class="lnysw87pu wm-k"/><path class="cxeqomklq wm-k"/><path class="h_xsybc4i wm-k"/><path class="uu_mg3b0v wm-shine"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:pound-sterling" {...props}></Icon>
