<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/avuc086wx.css';
import '../../css/g/g4vf-sb9r.css';
import '../../css/u/ucqk0cbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="avuc086wx wm-k"/><path class="g4vf-sb9r wm-k"/><path class="ucqk0cbzc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-2-sketch" {...props}></Icon>
