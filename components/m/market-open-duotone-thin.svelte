<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9kutnf3b"/><path class="ttx6bbv4v"/><path class="ts5r08i7u"/><path class="vdzoqccgg"/><path class="baci-hp8s"/><path class="ja-d7-b4a"/><path class="ic_pehd5a"/><path class="gyu499fcn"/><path class="k4y331wag"/><path class="xdvtlk8qz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:market-open-duotone-thin" {...props}></Icon>
<style>
:global(.baci-hp8s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19.5 9.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gyu499fcn) {
  d: path("M12 6v2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.ja-d7-b4a) {
  d: path("M6 17a6 6 0 0 1 12 0");
}

:global(.k4y331wag) {
  d: path("m4.5 9.5 2 2");
}

:global(.r9kutnf3b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 17a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ts5r08i7u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ttx6bbv4v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vdzoqccgg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4.5 9.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xdvtlk8qz) {
  d: path("m19.5 9.5 -2 2");
}

</style>
