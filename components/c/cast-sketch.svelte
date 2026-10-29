<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/od1pjlbrn.css';
import '../../css/a/akiqotlgz.css';
import '../../css/h/hmemabbvr.css';
import '../../css/k/k2u-005rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="od1pjlbrn wm-k"/><path class="akiqotlgz wm-a"/><path class="hmemabbvr wm-k"/><path class="k2u-005rj wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cast-sketch" {...props}></Icon>
