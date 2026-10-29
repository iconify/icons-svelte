<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gsxicobdl.css';
import '../../css/t/tzpkcedjf.css';
import '../../css/o/ov2wiebyk.css';
import '../../css/s/s1ykx_bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gsxicobdl"/><path class="tzpkcedjf wm-a"/><path class="ov2wiebyk wm-k"/><path class="s1ykx_bri wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-circle-sketch" {...props}></Icon>
