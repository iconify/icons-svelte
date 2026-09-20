<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a5yfw13jk"/><path class="zka_zabrc"/><path class="kdybz_aht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funeral-outline-regular" {...props}></Icon>
<style>
:global(.a5yfw13jk) {
  d: path("M6 21V10c0 -5 12 -5 12 0v11Z");
}

:global(.kdybz_aht) {
  d: path("M9 17h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zka_zabrc) {
  d: path("M9 13h6");
}

</style>
