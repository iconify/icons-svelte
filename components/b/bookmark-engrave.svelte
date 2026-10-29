<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qxi7yn2rl.css';
import '../../css/n/n8q0-sbxu.css';
import '../../css/m/me3qcxbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qxi7yn2rl"/><path class="n8q0-sbxu wm-shadow"/><path class="me3qcxbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-engrave" {...props}></Icon>
