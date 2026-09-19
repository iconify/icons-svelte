<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/f/f0j3glb_n.css';
import '../../css/l/lio3osqhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><circle class="f0j3glb_n"/><path class="lio3osqhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-1-bold" {...props}></Icon>
