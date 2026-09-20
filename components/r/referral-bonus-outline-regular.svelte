<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="oewjtrp_y"/><path class="z8jb6te8i"/><path class="ijxaf0bnr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:referral-bonus-outline-regular" {...props}></Icon>
<style>
:global(.ijxaf0bnr) {
  d: path("M7 17.5h10");
}

:global(.k6fi9qmtq) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oewjtrp_y) {
  d: path("M7 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ozi-k-boi) {
  d: path("M3 7h18");
}

:global(.z8jb6te8i) {
  d: path("M13 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
