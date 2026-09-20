<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dx0l4abna"/><path class="r4v0xr3qy"/><path class="p8a7rmkzk"/><path class="eev_c9mlp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-up-duotone-thin" {...props}></Icon>
<style>
:global(.dx0l4abna) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 4 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eev_c9mlp) {
  d: path("m7 20 5 -5 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8a7rmkzk) {
  d: path("m7 4 5 5 5 -5");
}

:global(.r4v0xr3qy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 20 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
