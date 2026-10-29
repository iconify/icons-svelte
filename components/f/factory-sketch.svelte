<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b6r623bpq.css';
import '../../css/w/wmfn8sbna.css';
import '../../css/e/ew51tmbbl.css';
import '../../css/c/cvqya5bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b6r623bpq"/><path class="wm-k wmfn8sbna"/><path class="ew51tmbbl wm-k"/><path class="cvqya5bkd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:factory-sketch" {...props}></Icon>
