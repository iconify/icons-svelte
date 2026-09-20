<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hspeesv2z"/><path class="ujt25lh2u"/><path class="tv6hbrcra"/><path class="kh6ih_cgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:paused-goal-outline-regular" {...props}></Icon>
<style>
:global(.hspeesv2z) {
  d: path("M5.5 3v5.5a6.5 6.5 0 0 0 13 0V3");
}

:global(.kh6ih_cgl) {
  d: path("M9 6h6l-6 6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tv6hbrcra) {
  d: path("M8.5 20.5h7");
}

:global(.ujt25lh2u) {
  d: path("M12 15v5.5");
}

</style>
