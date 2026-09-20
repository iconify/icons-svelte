<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iaozfqbuj"/><path class="tuv2qrbve"/><path class="z28ycwbis"/><path class="cjc0mqb2o"/><path class="z6ec0ccup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-swap-outline-regular" {...props}></Icon>
<style>
:global(.cjc0mqb2o) {
  d: path("M9 14h7");
}

:global(.iaozfqbuj) {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tuv2qrbve) {
  d: path("M8 10h7");
}

:global(.z28ycwbis) {
  d: path("m13 8 2 2 -2 2");
}

:global(.z6ec0ccup) {
  d: path("m11 12 -2 2 2 2");
}

</style>
