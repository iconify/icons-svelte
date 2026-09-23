<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xax07rbgn.css';
import '../../css/q/q-4sndczh.css';
import '../../css/a/aluo5vbsb.css';
import '../../css/i/iq1f_7bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xax07rbgn"/><path class="q-4sndczh"/><path class="aluo5vbsb"/><path class="iq1f_7bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:refresh-cw-sparkles-sharp-duotone" {...props}></Icon>
