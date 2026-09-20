<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdeiv7bia"/><path class="ke8s6xb3g"/><path class="c7-22ebqd"/><path class="bx9u4o00v"/><path class="qvu33mb1p"/><path class="et-iwmblh"/><path class="nqnw98byf"/><path class="f0qz9mbvk"/><path class="t3iybibvf"/><path class="wbz8a-gmi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bed-duotone-thin" {...props}></Icon>
<style>
:global(.bx9u4o00v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c7-22ebqd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11V7h6v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.et-iwmblh) {
  d: path("M2 18v-7h20v7");
}

:global(.f0qz9mbvk) {
  d: path("M4 11V7h6v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ke8s6xb3g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nqnw98byf) {
  d: path("M2 14h20");
}

:global(.qvu33mb1p) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 18v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3iybibvf) {
  d: path("M3 18v2.5");
}

:global(.wbz8a-gmi) {
  d: path("M21 18v2.5");
}

:global(.zdeiv7bia) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
