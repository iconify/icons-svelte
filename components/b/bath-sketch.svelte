<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zxmf3xbzu.css';
import '../../css/o/oc_p2dhlj.css';
import '../../css/q/q3ad9d2ky.css';
import '../../css/z/ziso84b9n.css';
import '../../css/u/uxoz16zip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zxmf3xbzu"/><path class="oc_p2dhlj wm-k"/><path class="q3ad9d2ky wm-a"/><path class="wm-k ziso84b9n"/><path class="uxoz16zip wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bath-sketch" {...props}></Icon>
