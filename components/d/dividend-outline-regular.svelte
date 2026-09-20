<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-4bk_b4n"/><path class="oej_05bgt"/><path class="lp4aq-bgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dividend-outline-regular" {...props}></Icon>
<style>
:global(.lp4aq-bgr) {
  d: path("M14 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o-4bk_b4n) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

:global(.oej_05bgt) {
  d: path("M4 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
