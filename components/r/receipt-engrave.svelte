<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gr9--r07w.css';
import '../../css/o/oi26-bbrd.css';
import '../../css/r/ri2oegbdi.css';
import '../../css/p/perttu9bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gr9--r07w wm-k"/><path class="oi26-bbrd wm-shadow"/><path class="ri2oegbdi wm-k"/><path class="perttu9bq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:receipt-engrave" {...props}></Icon>
