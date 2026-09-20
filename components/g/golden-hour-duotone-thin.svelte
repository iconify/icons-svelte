<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq88vobtv"/><path class="ior14cbcm"/><path class="mslqadb-r"/><path class="ef4akx9wy"/><path class="tkammbbef"/><path class="p82b3hbgt"/><path class="grgwcd1mp"/><path class="z9ittvbis"/><path class="h4br4z40f"/><path class="e0fatccfd"/><path class="sdu5ckfnu"/><path class="sxnekjbzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:golden-hour-duotone-thin" {...props}></Icon>
<style>
:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.ef4akx9wy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eq88vobtv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.grgwcd1mp) {
  d: path("M7.5 17a4.5 4.5 0 0 1 9 0");
}

:global(.h4br4z40f) {
  d: path("M2 12h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ior14cbcm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mslqadb-r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p82b3hbgt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 6 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sdu5ckfnu) {
  d: path("m5 6 3 3");
}

:global(.sxnekjbzh) {
  d: path("m19 6 -3 3");
}

:global(.tkammbbef) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 6 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
