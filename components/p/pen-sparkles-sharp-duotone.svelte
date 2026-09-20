<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/jef8rhbsn.css';
import '../../css/b/bu7no646v.css';
import '../../css/c/c_xk-lr_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jef8rhbsn"/><path class="bu7no646v"/><path class="c_xk-lr_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pen-sparkles-sharp-duotone" {...props}></Icon>
