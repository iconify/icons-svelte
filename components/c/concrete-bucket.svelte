<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hy_bpejoi"/><path class="kbd6tvbsv"/><path class="ah8dyvw5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:concrete-bucket" {...props}></Icon>
<style>
:global(.ah8dyvw5d) {
  d: path("m6.593 11.751l10.799 1.045a1.75 1.75 0 0 1 1.51 2.236l-1.533 5.212a1.75 1.75 0 0 1-1.678 1.256H8.302a1.75 1.75 0 0 1-1.676-1.247l-1.877-6.257a1.75 1.75 0 0 1 1.844-2.245");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hy_bpejoi) {
  d: path("M13.75 2.5v3c0 2.75-3.5 2.75-3.5.5");
}

:global(.kbd6tvbsv) {
  d: path("m5 11.5l7-3.75L19 13");
}

</style>
