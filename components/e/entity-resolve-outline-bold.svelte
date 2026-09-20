<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dfcdzc65k"/><path class="aeyekmbly"/><path class="pxp27mb9k"/><path class="ks612kq_w"/><path class="kiksj5oln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:entity-resolve-outline-bold" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.dfcdzc65k) {
  d: path("M3 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kiksj5oln) {
  d: path("M12 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.ks612kq_w) {
  d: path("m7 17 5 -5");
}

:global(.pxp27mb9k) {
  d: path("m7 7 5 5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
