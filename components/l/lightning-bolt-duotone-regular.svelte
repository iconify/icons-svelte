<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz1z5bc0f"/><path class="nvmq33b0q"/><path class="ctm-gvblg"/><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lightning-bolt-duotone-regular" {...props}></Icon>
<style>
:global(.ctm-gvblg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 14 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flblq5ico) {
  d: path("m13 14 6 6");
}

:global(.lz1z5bc0f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 2 -8 8h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbgtdkbsk) {
  d: path("m16 2 -8 8h5l-8 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nvmq33b0q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m13 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zsil77j-s) {
  d: path("m19 14 -6 6");
}

</style>
