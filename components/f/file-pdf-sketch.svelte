<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cw41ftbat.css';
import '../../css/d/d-9pp_qrb.css';
import '../../css/t/tmmgayb5u.css';
import '../../css/g/gz2kprb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cw41ftbat"/><path class="d-9pp_qrb wm-a"/><path class="tmmgayb5u wm-k"/><path class="gz2kprb8a wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-pdf-sketch" {...props}></Icon>
