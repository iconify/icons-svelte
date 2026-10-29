<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q0zjfeb9r.css';
import '../../css/k/kz6nbfeim.css';
import '../../css/u/ucexqlbld.css';
import '../../css/l/ly5598bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q0zjfeb9r wm-k"/><path class="kz6nbfeim wm-shadow"/><path class="ucexqlbld wm-k"/><path class="ly5598bwp wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-check-big-engrave" {...props}></Icon>
