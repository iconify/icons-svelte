<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpvjsebmn"/><path class="olvpjxutl"/><path class="efp7jr93m"/><path class="eb5zxsbop"/><path class="h-2cwy44u"/><path class="dahw1rbat"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crisis-line-duotone-thin" {...props}></Icon>
<style>
:global(.dahw1rbat) {
  d: path("M18 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.eb5zxsbop) {
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
}

:global(.efp7jr93m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 3v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-2cwy44u) {
  d: path("M19 3v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.olvpjxutl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5a2 2 0 0 1 4 0v3a2 2 0 0 1 -4 0Zm0 3c0 6 6 12 12 12m0 0a2 2 0 0 0 4 0v-3a2 2 0 0 0 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rpvjsebmn) {
  fill: currentColor;
  d: path("M18 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
