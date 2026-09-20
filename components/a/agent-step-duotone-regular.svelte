<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gntt6lljd"/><path class="kt9ytgb-j"/><path class="dxqp15kpa"/><path class="klyrig6if"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-step-duotone-regular" {...props}></Icon>
<style>
:global(.dxqp15kpa) {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.gntt6lljd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.klyrig6if) {
  d: path("m14 7 5 5 -5 5");
}

:global(.kt9ytgb-j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
