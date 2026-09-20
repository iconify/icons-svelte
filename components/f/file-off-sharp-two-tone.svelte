<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/g/g5ncw42dh.css';
import '../../css/q/q5hmxc_qj.css';
import '../../css/i/iyreedmkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g5ncw42dh"/><path class="q5hmxc_qj"/><path class="iyreedmkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-off-sharp-two-tone" {...props}></Icon>
