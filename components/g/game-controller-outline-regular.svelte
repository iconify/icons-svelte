<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="te6l0fu1w"/><path class="emd5ykbgi"/><path class="lymn1951z"/><path class="me7c_bbry"/><path class="ec5tld62j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-controller-outline-regular" {...props}></Icon>
<style>
:global(.ec5tld62j) {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.emd5ykbgi) {
  d: path("M8 10v4");
}

:global(.lymn1951z) {
  d: path("M6 12h4");
}

:global(.me7c_bbry) {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.te6l0fu1w) {
  d: path("M7 7h10c2.5 0 4 3 4 7 0 3 -1 5 -3 5s-3 -3 -6 -3 -4 3 -6 3 -3 -2 -3 -5c0 -4 1.5 -7 4 -7");
}

</style>
