<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kf-dg5j1v"/><path class="s09hy0b0y"/><path class="rx24zrjxq"/><path class="acx2mjbnt"/><path class="ftrg70bds"/><path class="jkuojibnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gardening-outline-bold" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.ftrg70bds) {
  d: path("M17 11v6");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.kf-dg5j1v) {
  d: path("M12 2v9");
}

:global(.rx24zrjxq) {
  d: path("M7 11v6");
}

:global(.s09hy0b0y) {
  d: path("M7 11h10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
