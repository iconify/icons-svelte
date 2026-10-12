<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nq__ccb6w"/><circle class="m1is5jemp"/><circle class="x45ounoqa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cell-division" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1is5jemp) {
  cx: 7.75px;
  cy: 12px;
  r: 2px;
}

:global(.nq__ccb6w) {
  d: path("M12 9.37a5 5 0 1 0 0 5.26a5 5 0 1 0 0-5.26");
}

:global(.x45ounoqa) {
  cx: 16.25px;
  cy: 12px;
  r: 2px;
}

</style>
