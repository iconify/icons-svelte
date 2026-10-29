<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/j_ndhtijc.css';
import '../../css/a/abdpkjbfc.css';
import '../../css/w/wi57tslpl.css';
import '../../css/s/sx0or_bfv.css';
import '../../css/q/qb8yovbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="j_ndhtijc"/><path class="abdpkjbfc wm-k"/><path class="wi57tslpl wm-a"/><path class="sx0or_bfv"/><path class="qb8yovbej wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:eye-off-sketch" {...props}></Icon>
