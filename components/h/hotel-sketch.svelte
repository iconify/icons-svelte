<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sdf38muvh.css';
import '../../css/f/fet2cqbea.css';
import '../../css/g/g63vy454t.css';
import '../../css/t/tubrnps1o.css';
import '../../css/f/fd_m9bqpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sdf38muvh wm-k"/><path class="fet2cqbea wm-k"/><path class="g63vy454t wm-k"/><path class="tubrnps1o wm-s"/><path class="fd_m9bqpc wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hotel-sketch" {...props}></Icon>
