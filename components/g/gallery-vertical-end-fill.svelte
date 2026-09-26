<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a65dndbws"/><path class="btw_rsbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gallery-vertical-end-fill" {...props}></Icon>
<style>
:global(.a65dndbws) {
  fill: currentColor;
  d: path("M5 10L19 10C20.65685 10 22 11.34315 22 13L22 19C22 20.65685 20.65685 22 19 22L5 22C3.34315 22 2 20.65685 2 19L2 13C2 11.34315 3.34315 10 5 10Z");
  stroke: none;
}

:global(.btw_rsbbl) {
  d: path("M5 7H19M7 3H17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
