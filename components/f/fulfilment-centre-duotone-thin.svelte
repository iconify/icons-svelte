<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nwi87ac4g"/><path class="e8rfc8bkg"/><path class="b8byr4b5i"/><path class="e77gki8ci"/><path class="mvm7r4bea"/><path class="yt5ezyvwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fulfilment-centre-duotone-thin" {...props}></Icon>
<style>
:global(.b8byr4b5i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 11.5 16 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e77gki8ci) {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

:global(.e8rfc8bkg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 14h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mvm7r4bea) {
  d: path("M8 14h8");
}

:global(.nwi87ac4g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yt5ezyvwf) {
  d: path("M13.5 11.5 16 14l-2.5 2.5");
}

</style>
