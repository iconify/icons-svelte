<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="ayk-facnc"/><path class="ukpi_e5ue"/><path class="nntrnih8q"/><path class="jfxr4h1vm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:okr-target" {...props}></Icon>
<style>
:global(.ayk-facnc) {
  cx: 12px;
  cy: 8.5px;
  r: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfxr4h1vm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 17.5h14.5M4.75 21h8.5");
}

:global(.nntrnih8q) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.5h.01");
}

:global(.ukpi_e5ue) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.75a2.75 2.75 0 1 0 0 5.5a2.75 2.75 0 1 0 0-5.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
