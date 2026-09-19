<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/f/f0j3glb_n.css';
import '../../css/l/lio3osqhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="f0j3glb_n"/><path class="lio3osqhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-1-thin" {...props}></Icon>
