<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ibm9srp6n.css';
import '../../css/m/mnkn6ibxr.css';
import '../../css/u/ukl0y6blj.css';
import '../../css/t/t-u8hzbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ibm9srp6n"/><path class="mnkn6ibxr wm-k"/><path class="ukl0y6blj wm-a"/><path class="t-u8hzbyc wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cauldron-sketch" {...props}></Icon>
