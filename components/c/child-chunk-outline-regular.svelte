<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i-xag2bkh"/><path class="mxzk029nb"/><path class="kzek4ybzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:child-chunk-outline-regular" {...props}></Icon>
<style>
:global(.i-xag2bkh) {
  d: path("M3 6.5A3.5 3.5 0 0 1 6.5 3h11A3.5 3.5 0 0 1 21 6.5a3.5 3.5 0 0 1 -3.5 3.5h-11A3.5 3.5 0 0 1 3 6.5");
}

:global(.kzek4ybzp) {
  d: path("M7 17a3 3 0 0 1 3 -3h4a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-4a3 3 0 0 1 -3 -3");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
