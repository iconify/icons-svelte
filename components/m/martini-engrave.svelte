<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/co6ufk7zc.css';
import '../../css/r/rgpf1zbjs.css';
import '../../css/y/yo87urbrl.css';
import '../../css/d/d5_gd2mux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="co6ufk7zc"/><path class="rgpf1zbjs wm-shadow"/><path class="yo87urbrl"/><path class="d5_gd2mux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:martini-engrave" {...props}></Icon>
