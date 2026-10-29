<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kd18vnk4i.css';
import '../../css/t/txreq5qxj.css';
import '../../css/o/ovqg6xbyk.css';
import '../../css/b/b1foumd7v.css';
import '../../css/c/cka-0ib4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kd18vnk4i"/><path class="txreq5qxj wm-a"/><path class="ovqg6xbyk wm-k"/><path class="b1foumd7v wm-a"/><path class="cka-0ib4x wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-lock-sketch" {...props}></Icon>
