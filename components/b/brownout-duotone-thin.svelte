<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jilnjmblz"/><path class="eu82ces9t"/><path class="hb5bs7bvv"/><path class="kdybz_aht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:brownout-duotone-thin" {...props}></Icon>
<style>
:global(.eu82ces9t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 17h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hb5bs7bvv) {
  d: path("M13 3 8 8h3.5l-5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jilnjmblz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 3 8 8h3.5l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kdybz_aht) {
  d: path("M9 17h6");
}

</style>
