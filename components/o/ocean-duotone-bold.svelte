<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gt2efwopc"/><path class="ola702blo"/><path class="ljevkdbdx"/><path class="lmj_kj__f"/><path class="oy_r10b4z"/><path class="yzilgtbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ocean-duotone-bold" {...props}></Icon>
<style>
:global(.gt2efwopc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ljevkdbdx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmj_kj__f) {
  d: path("m3 8 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.ola702blo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oy_r10b4z) {
  d: path("m3 14 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yzilgtbzd) {
  d: path("m3 20 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
