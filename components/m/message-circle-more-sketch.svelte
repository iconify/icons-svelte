<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fg3cv2kdo.css';
import '../../css/k/k22g0i2az.css';
import '../../css/j/jo6urw9ef.css';
import '../../css/d/dv5lb9b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fg3cv2kdo"/><path class="k22g0i2az wm-k"/><path class="jo6urw9ef wm-k"/><path class="dv5lb9b_r wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:message-circle-more-sketch" {...props}></Icon>
