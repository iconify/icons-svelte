<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="yf_brbf0s"/><path class="a2i99ybke"/><path class="ca8fh52yx"/><path class="xgrfb-bqu"/><path class="d8abqfbpc"/><path class="ehxfnqbrv"/><path class="rx4ch-ouz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ltr-duotone-thin" {...props}></Icon>
<style>
:global(.a2i99ybke) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ca8fh52yx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 14.5 18 17l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ehxfnqbrv) {
  d: path("M3 17h15");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rx4ch-ouz) {
  d: path("M15.5 14.5 18 17l-2.5 2.5");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.yf_brbf0s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
