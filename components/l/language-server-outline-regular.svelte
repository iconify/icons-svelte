<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r35682biw"/><path class="s99q9ducq"/><path class="l75boxf1g"/><path class="fyu0dwbqf"/><path class="m-rtkii6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:language-server-outline-regular" {...props}></Icon>
<style>
:global(.fyu0dwbqf) {
  d: path("M9 16v3.5");
}

:global(.l75boxf1g) {
  d: path("m16 7 2.5 2.5L16 12");
}

:global(.m-rtkii6v) {
  d: path("M15 16v3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r35682biw) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.s99q9ducq) {
  d: path("M8 7 5.5 9.5 8 12");
}

</style>
