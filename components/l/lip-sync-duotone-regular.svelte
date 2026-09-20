<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1tghrmcy"/><path class="swbedxnvn"/><path class="ktqguibjo"/><path class="ydk-7sp0t"/><path class="iprvt7beg"/><path class="fijjj9b9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lip-sync-duotone-regular" {...props}></Icon>
<style>
:global(.fijjj9b9u) {
  d: path("M20.54 6.46a5 5 0 0 1 0 7.08");
}

:global(.iprvt7beg) {
  d: path("M19.12 7.88a3 3 0 0 1 0 4.24");
}

:global(.ktqguibjo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20.54 6.46a5 5 0 0 1 0 7.08");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.swbedxnvn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.12 7.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w1tghrmcy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 10a5.5 5.5 0 0 1 -11 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ydk-7sp0t) {
  d: path("M14.5 10a5.5 5.5 0 0 1 -11 0");
}

</style>
