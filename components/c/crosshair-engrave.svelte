<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ewez7_93d.css';
import '../../css/o/ogzm1vbyu.css';
import '../../css/k/kxrjztx3q.css';
import '../../css/z/zc2m5bbql.css';
import '../../css/d/d4rt0lb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ewez7_93d wm-k"/><path class="ogzm1vbyu wm-a"/><path class="kxrjztx3q wm-shadow"/><path class="wm-k zc2m5bbql"/><path class="d4rt0lb-l wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crosshair-engrave" {...props}></Icon>
