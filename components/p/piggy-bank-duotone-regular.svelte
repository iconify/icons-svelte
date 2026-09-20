<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c-ue9sb-d"/><path class="p88ypbxwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:piggy-bank-duotone-regular" {...props}></Icon>
<style>
:global(.c-ue9sb-d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12.5a7 7 0 1 1 14 0 7 7 0 1 1 -14 0m12 -2h5v4h-5M7.5 19v3m7 -3v3m-5 -19v2.5m6 2.5 2 -2 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p88ypbxwz) {
  d: path("M4 12.5a7 7 0 1 1 14 0 7 7 0 1 1 -14 0m12 -2h5v4h-5M7.5 19v3m7 -3v3m-5 -19v2.5m6 2.5 2 -2 2 2");
}

</style>
