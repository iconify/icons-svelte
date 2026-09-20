<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tt1gaezch"/><path class="q3wfxmb7j"/><path class="piaam4vpr"/><path class="i67dqei2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-left-duotone-regular" {...props}></Icon>
<style>
:global(.i67dqei2u) {
  d: path("M4 10v10h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.piaam4vpr) {
  d: path("M20 4 4 20");
}

:global(.q3wfxmb7j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v10h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tt1gaezch) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 4 4 20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
