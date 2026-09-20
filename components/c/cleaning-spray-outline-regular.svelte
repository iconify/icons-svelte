<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f8ggyj7xo"/><path class="ht122hbxe"/><path class="wvj5idbgl"/><path class="fn3ujkbay"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cleaning-spray-outline-regular" {...props}></Icon>
<style>
:global(.f8ggyj7xo) {
  d: path("M7 10v11h8V10Z");
}

:global(.fn3ujkbay) {
  d: path("M19 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ht122hbxe) {
  d: path("M9 10V5h6v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wvj5idbgl) {
  d: path("M17 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
