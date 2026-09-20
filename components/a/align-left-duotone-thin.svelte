<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="cv60iqboi"/><path class="grr8qubal"/><path class="xgrfb-bqu"/><path class="x22av82oi"/><path class="cn-9z7b7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-left-duotone-thin" {...props}></Icon>
<style>
:global(.cn-9z7b7f) {
  d: path("M3 18h15");
}

:global(.cv60iqboi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.grr8qubal) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
