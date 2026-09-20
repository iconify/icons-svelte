<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="fea--0b8r"/><path class="nkt0f5bif"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="duvzkqbwy"/><path class="m6r9k7-tj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:invariant-duotone-regular" {...props}></Icon>
<style>
:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.duvzkqbwy) {
  d: path("M8 9.5h8");
}

:global(.fea--0b8r) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ku_telleq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.m6r9k7-tj) {
  d: path("M8 14.5h8");
}

:global(.nkt0f5bif) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 14.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wywiukbgn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
