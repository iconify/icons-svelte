<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ixdgj062g"/><path class="lqiw_3bos"/><path class="gorvssbqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:data-exfil-outline-bold" {...props}></Icon>
<style>
:global(.gorvssbqo) {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

:global(.ixdgj062g) {
  d: path("M3 6a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.lqiw_3bos) {
  d: path("M10 12h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
