<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exvvozbzj"/><path class="crt2xgbyp"/><path class="bqnb7_3lf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:band-ring" {...props}></Icon>
<style>
:global(.bqnb7_3lf) {
  d: path("M6 10.25a6 2 0 1 0 12 0a6 2 0 1 0-12 0");
}

:global(.crt2xgbyp) {
  d: path("M3 10.25v3.25a9 5.25 0 0 0 18 0v-3.25");
}

:global(.exvvozbzj) {
  d: path("M3 10.25a9 5.25 0 1 0 18 0a9 5.25 0 1 0-18 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
