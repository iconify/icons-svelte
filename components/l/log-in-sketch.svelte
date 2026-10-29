<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l4ne79z1h.css';
import '../../css/o/ok0419bhs.css';
import '../../css/v/vt7mo6bvk.css';
import '../../css/t/tfxarxbqc.css';
import '../../css/o/owcf405tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l4ne79z1h"/><path class="ok0419bhs wm-k"/><path class="vt7mo6bvk wm-a"/><path class="tfxarxbqc wm-k"/><path class="owcf405tn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:log-in-sketch" {...props}></Icon>
