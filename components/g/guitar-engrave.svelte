<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oubg7rbmf.css';
import '../../css/n/na0fz3f1u.css';
import '../../css/e/ed5dmbefl.css';
import '../../css/k/knf-w_g_n.css';
import '../../css/c/c96fvtbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oubg7rbmf wm-k"/><path class="na0fz3f1u wm-a"/><path class="ed5dmbefl wm-shadow"/><path class="knf-w_g_n wm-k"/><path class="c96fvtbfs wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:guitar-engrave" {...props}></Icon>
