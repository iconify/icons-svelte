<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9kj30b9l"/><path class="ijf5g-qwb"/><path class="beu00o73l"/><path class="zc_8qdb6u"/><path class="zifm62gud"/><path class="q95wyyyjq"/><path class="t407ddc6o"/><path class="dcemxxfpc"/><path class="uv_v7wb2g"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:few-shot-duotone-thin" {...props}></Icon>
<style>
:global(.beu00o73l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d9kj30b9l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dcemxxfpc) {
  d: path("M3 19h8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ijf5g-qwb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q95wyyyjq) {
  d: path("M3 5h8");
}

:global(.t407ddc6o) {
  d: path("M3 12h8");
}

:global(.uv_v7wb2g) {
  d: path("M14 12h5");
}

:global(.zc_8qdb6u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zifm62gud) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
