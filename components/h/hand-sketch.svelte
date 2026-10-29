<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rf8yh-27v.css';
import '../../css/l/llsjouo2v.css';
import '../../css/g/g_sh4b3bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rf8yh-27v"/><path class="llsjouo2v"/><path class="g_sh4b3bp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hand-sketch" {...props}></Icon>
