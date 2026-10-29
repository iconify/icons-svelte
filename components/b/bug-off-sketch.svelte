<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a7tavubsc.css';
import '../../css/l/ljoi_ccxk.css';
import '../../css/s/sxb24_b7l.css';
import '../../css/i/ibx6rmbwp.css';
import '../../css/q/qo_js1bba.css';
import '../../css/b/brldgzb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a7tavubsc wm-k"/><path class="ljoi_ccxk wm-a"/><path class="sxb24_b7l wm-s"/><path class="ibx6rmbwp wm-k"/><path class="qo_js1bba wm-a"/><path class="brldgzb2h wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bug-off-sketch" {...props}></Icon>
