<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xa1ukquey"/><path class="ih_hzbmoj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:inventory-count-duotone-regular" {...props}></Icon>
<style>
:global(.ih_hzbmoj) {
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xa1ukquey) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 20v-8h16v8Zm8 -8v8m-4 -8V4h8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
