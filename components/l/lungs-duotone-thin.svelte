<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnn9fzquj"/><path class="hzfq82b-n"/><path class="nnwao2bjn"/><path class="gn4faibes"/><path class="z60jnpbbk"/><path class="x7f1-zoxp"/><path class="frl4q-b1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lungs-duotone-thin" {...props}></Icon>
<style>
:global(.frl4q-b1m) {
  d: path("M15 13v7a5 5 0 0 0 5 -5c0 -2 -2 -2 -5 -2");
}

:global(.gn4faibes) {
  d: path("m12 10 -3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hzfq82b-n) {
  fill: currentColor;
  d: path("M15 13v7a5 5 0 0 0 5 -5c0 -2 -2 -2 -5 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.jnn9fzquj) {
  fill: currentColor;
  d: path("M9 13v7a5 5 0 0 1 -5 -5c0 -2 2 -2 5 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nnwao2bjn) {
  d: path("M12 3v7");
}

:global(.x7f1-zoxp) {
  d: path("M9 13v7a5 5 0 0 1 -5 -5c0 -2 2 -2 5 -2");
}

:global(.z60jnpbbk) {
  d: path("m12 10 3 3");
}

</style>
