<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hb5bs7bvv"/><path class="kdybz_aht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:brownout-outline-regular" {...props}></Icon>
<style>
:global(.hb5bs7bvv) {
  d: path("M13 3 8 8h3.5l-5 5");
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

</style>
