<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkh6f026t"/><path class="x2p3-nb6i"/><path class="sgp7fvbwx"/><path class="rys8seqzf"/><path class="c1g0k8fft"/><path class="k6nj2fbya"/><path class="a6mnjib5x"/><path class="l8vricc3a"/><path class="t8troqb7m"/><path class="yngda3bvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:backfill-data-duotone-regular" {...props}></Icon>
<style>
:global(.a6mnjib5x) {
  d: path("M3 10h4");
}

:global(.c1g0k8fft) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 15h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.l8vricc3a) {
  d: path("M17 10h4");
}

:global(.mkh6f026t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rys8seqzf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sgp7fvbwx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t8troqb7m) {
  d: path("m10 9 2 2 2 -2");
}

:global(.x2p3-nb6i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 10h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yngda3bvc) {
  d: path("M3 15h18");
}

</style>
