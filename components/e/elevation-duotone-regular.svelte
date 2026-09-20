<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tfryo4bhy"/><path class="opio8j5fe"/><path class="wzcki-coh"/><path class="r3-bp3bbk"/><path class="f1um23b3l"/><path class="jor2cmbne"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:elevation-duotone-regular" {...props}></Icon>
<style>
:global(.f1um23b3l) {
  d: path("M4 19h17");
}

:global(.jor2cmbne) {
  d: path("m6 16 4 -4 3 3 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.opio8j5fe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 19h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3-bp3bbk) {
  d: path("M4 3v16");
}

:global(.tfryo4bhy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wzcki-coh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 16 4 -4 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
