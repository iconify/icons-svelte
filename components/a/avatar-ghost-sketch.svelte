<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dnnmvmbax.css';
import '../../css/j/jrcx8qb1e.css';
import '../../css/s/s8xb1n54b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dnnmvmbax"/><path class="jrcx8qb1e wm-k"/><path class="s8xb1n54b wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-ghost-sketch" {...props}></Icon>
