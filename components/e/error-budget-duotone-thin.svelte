<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r30n85jvq"/><path class="h-x20cc3f"/><path class="coi-np7dk"/><path class="cypwq7brt"/><path class="rch9xfupi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:error-budget-duotone-thin" {...props}></Icon>
<style>
:global(.coi-np7dk) {
  d: path("M15 9v6");
}

:global(.cypwq7brt) {
  d: path("m17 4 4 4");
}

:global(.h-x20cc3f) {
  d: path("M2 15a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r30n85jvq) {
  fill: currentColor;
  d: path("M2 15a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rch9xfupi) {
  d: path("m21 4 -4 4");
}

</style>
