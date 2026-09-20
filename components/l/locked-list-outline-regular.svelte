<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aly6ip2cj"/><path class="zkjcegn9b"/><path class="c80skftax"/><path class="eud-3ptuk"/><path class="tk71h5gnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:locked-list-outline-regular" {...props}></Icon>
<style>
:global(.aly6ip2cj) {
  d: path("M2 13a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.c80skftax) {
  d: path("M15 8h7");
}

:global(.eud-3ptuk) {
  d: path("M15 12h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tk71h5gnp) {
  d: path("M15 16h7");
}

:global(.zkjcegn9b) {
  d: path("M4 11a3 3 0 0 1 6 0");
}

</style>
