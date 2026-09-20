<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t_iz9qbpi"/><path class="ei8gh2b1p"/><path class="gd8l1w4ql"/><path class="isrhyfbxd"/><path class="orxbg_b1j"/><path class="zuuudpbwi"/><path class="rdidnh2az"/><path class="isrkj8blm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dedupe-fuzzy-duotone-bold" {...props}></Icon>
<style>
:global(.ei8gh2b1p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gd8l1w4ql) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 11.5 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.isrhyfbxd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 17h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.isrkj8blm) {
  d: path("M3 17h13");
}

:global(.orxbg_b1j) {
  d: path("M3 4h13");
}

:global(.rdidnh2az) {
  d: path("m10 11.5 2 2 2 -2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t_iz9qbpi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuuudpbwi) {
  d: path("M3 8h14");
}

</style>
