<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v7n9ppbmt.css';
import '../../css/n/n8q0-sbxu.css';
import '../../css/m/me3qcxbaj.css';
import '../../css/m/meogk_ylc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v7n9ppbmt wm-k"/><path class="n8q0-sbxu wm-shadow"/><path class="me3qcxbaj wm-k"/><path class="meogk_ylc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-check-engrave" {...props}></Icon>
