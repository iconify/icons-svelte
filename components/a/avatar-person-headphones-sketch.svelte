<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vn64pd1yg.css';
import '../../css/w/whghrwqec.css';
import '../../css/s/shx_j6b-f.css';
import '../../css/g/gkoajyd-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vn64pd1yg wm-k"/><path class="whghrwqec wm-a"/><path class="shx_j6b-f wm-k"/><path class="gkoajyd-t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-headphones-sketch" {...props}></Icon>
