<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tz_xhobck"/><path class="mkh6f026t"/><path class="lo-jzcbdp"/><path class="k6nj2fbya"/><path class="bg2ejdbaq"/><path class="bb_62lblh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:debit-duotone-regular" {...props}></Icon>
<style>
:global(.bb_62lblh) {
  d: path("M5.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bg2ejdbaq) {
  d: path("M12 5v16");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.lo-jzcbdp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mkh6f026t) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tz_xhobck) {
  fill: currentColor;
  d: path("M5.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
