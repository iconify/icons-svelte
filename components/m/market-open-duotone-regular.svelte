<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mvjfazm9f"/><path class="wfd9yacqd"/><path class="o7p0jrvbf"/><path class="uml9n3nle"/><path class="ti-6j3bms"/><path class="ja-d7-b4a"/><path class="ic_pehd5a"/><path class="gyu499fcn"/><path class="k4y331wag"/><path class="xdvtlk8qz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:market-open-duotone-regular" {...props}></Icon>
<style>
:global(.gyu499fcn) {
  d: path("M12 6v2.5");
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

:global(.mvjfazm9f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 17a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o7p0jrvbf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 6v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ti-6j3bms) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19.5 9.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uml9n3nle) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4.5 9.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wfd9yacqd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xdvtlk8qz) {
  d: path("m19.5 9.5 -2 2");
}

</style>
