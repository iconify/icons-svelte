<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i53j-vblo.css';
import '../../css/n/nij4fkuoc.css';
import '../../css/t/tcx9a37pv.css';
import '../../css/k/ko9c-gbhs.css';
import '../../css/r/rakss8bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i53j-vblo wm-k"/><path class="nij4fkuoc wm-a"/><path class="tcx9a37pv wm-shadow"/><path class="ko9c-gbhs wm-k"/><path class="rakss8bxv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-up-right-engrave" {...props}></Icon>
