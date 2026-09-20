<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ah1ap4vpp"/><path class="k38v4qb6f"/><path class="yvgc3wkxj"/><path class="elmoo_bpw"/><path class="q518x4bkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:front-door-duotone-regular" {...props}></Icon>
<style>
:global(.ah1ap4vpp) {
  fill: currentColor;
  d: path("M5 21V5h14v16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.elmoo_bpw) {
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.k38v4qb6f) {
  fill: currentColor;
  d: path("M15 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q518x4bkb) {
  d: path("M5 9h14");
}

:global(.yvgc3wkxj) {
  d: path("M5 21V5h14v16Z");
}

</style>
