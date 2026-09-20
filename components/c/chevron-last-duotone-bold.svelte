<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="huded_cfc"/><path class="j_m2_nbag"/><path class="xao2ebc6f"/><path class="tb3edh0qa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevron-last-duotone-bold" {...props}></Icon>
<style>
:global(.huded_cfc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j_m2_nbag) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tb3edh0qa) {
  d: path("m5 5 7 7 -7 7");
}

:global(.xao2ebc6f) {
  d: path("M21 5v14");
}

</style>
