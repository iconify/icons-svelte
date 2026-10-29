<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hbcxszb3z.css';
import '../../css/n/nr4l37b1c.css';
import '../../css/p/pezn3_bhe.css';
import '../../css/a/aa11gz0eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hbcxszb3z"/><path class="nr4l37b1c wm-a"/><path class="pezn3_bhe wm-k"/><path class="aa11gz0eb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-concierge-sketch" {...props}></Icon>
