<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tstyxkmej.css';
import '../../css/k/k3qcgxbnp.css';
import '../../css/i/iw07ocizs.css';
import '../../css/f/fmvl9jb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tstyxkmej wm-k"/><path class="k3qcgxbnp wm-shadow"/><path class="iw07ocizs wm-k"/><path class="fmvl9jb-y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refrigerator-engrave" {...props}></Icon>
