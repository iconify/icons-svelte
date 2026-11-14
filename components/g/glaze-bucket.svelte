<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="daleljbad"/><path class="mpals-bsz"/><path class="xkke1y1fe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:glaze-bucket" {...props}></Icon>
<style>
:global(.daleljbad) {
  d: path("M5 8.5h14L17.5 21h-11Z");
}

:global(.mpals-bsz) {
  d: path("M12 14.5a6 6 0 0 1 0-12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xkke1y1fe) {
  d: path("M5.25 11.5H9.5V15a1.25 1.25 0 0 0 2.5 0v-3.5h6.75");
}

</style>
