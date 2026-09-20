<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6nj2fbya"/><path class="g54o33why"/><path class="g0fpbbc_s"/><path class="pt0xyi7kd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pii-redact-outline-regular" {...props}></Icon>
<style>
:global(.g0fpbbc_s) {
  d: path("M18 11h3");
}

:global(.g54o33why) {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pt0xyi7kd) {
  d: path("M3 17h10");
}

</style>
