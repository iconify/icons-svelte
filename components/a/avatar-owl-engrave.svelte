<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k0whgccsu.css';
import '../../css/o/oa36macpv.css';
import '../../css/p/p2a6veb4f.css';
import '../../css/r/rf4h7ccos.css';
import '../../css/b/bjy30yb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k0whgccsu wm-k"/><path class="oa36macpv wm-a"/><path class="p2a6veb4f wm-shadow"/><path class="rf4h7ccos wm-k"/><path class="bjy30yb1k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-owl-engrave" {...props}></Icon>
