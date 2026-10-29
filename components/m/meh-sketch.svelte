<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qchn59f8p.css';
import '../../css/n/ns1jfzbcp.css';
import '../../css/q/qrfzbkdib.css';
import '../../css/v/vmlpc7vwr.css';
import '../../css/g/gke91ac6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qchn59f8p"/><path class="ns1jfzbcp wm-k"/><path class="qrfzbkdib wm-k"/><path class="vmlpc7vwr wm-a"/><path class="gke91ac6l wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:meh-sketch" {...props}></Icon>
