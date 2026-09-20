<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="orl97yk6g"/><path class="h-on-v7we"/><path class="d-kp91brx"/><path class="ior14cbcm"/><path class="i67oc1bla"/><path class="nzhcuvf_z"/><path class="mkk0o-9le"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:aurora-duotone-thin" {...props}></Icon>
<style>
:global(.d-kp91brx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-on-v7we) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i67oc1bla) {
  d: path("M5 16V8l4 -4");
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mkk0o-9le) {
  d: path("M15 16V8l4 -4");
}

:global(.nzhcuvf_z) {
  d: path("M10 16V8l4 -4");
}

:global(.orl97yk6g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 16V8l4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
