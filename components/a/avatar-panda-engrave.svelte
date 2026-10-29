<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/x8j_zkbgo.css';
import '../../css/d/dtmhvkbpr.css';
import '../../css/b/bbnnddbau.css';
import '../../css/m/mdvkx-geo.css';
import '../../css/x/xarb4rskp.css';
import '../../css/s/ssdqucc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k x8j_zkbgo"/><path class="dtmhvkbpr wm-a"/><path class="bbnnddbau wm-shadow"/><path class="mdvkx-geo wm-k"/><path class="wm-k xarb4rskp"/><path class="ssdqucc2z wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-panda-engrave" {...props}></Icon>
