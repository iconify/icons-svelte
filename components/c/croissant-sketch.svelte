<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/ld14kd3fo.css';
import '../../css/k/kj3ej9b7p.css';
import '../../css/h/hy_wfebxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ld14kd3fo wm-k"/><path class="kj3ej9b7p wm-k"/><path class="hy_wfebxz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:croissant-sketch" {...props}></Icon>
