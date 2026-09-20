<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mxbfiu5nj"/><path class="t8weryp5p"/><path class="xac31kual"/><path class="z_0m8vo0q"/><path class="t-0jg7bvk"/><path class="x4kxwubfs"/><path class="m0msdy1bm"/><path class="exo870qhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-duotone-thin" {...props}></Icon>
<style>
:global(.exo870qhz) {
  d: path("M15 11h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0msdy1bm) {
  d: path("M5 11h4");
}

:global(.mxbfiu5nj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t-0jg7bvk) {
  d: path("M12 7c-2 -2 -6 -3 -9 -2v14c3 -1 7 0 9 2");
}

:global(.t8weryp5p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x4kxwubfs) {
  d: path("M12 7c2 -2 6 -3 9 -2v14c-3 -1 -7 0 -9 2");
}

:global(.xac31kual) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z_0m8vo0q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 11h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
