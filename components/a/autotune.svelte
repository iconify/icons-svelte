<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghqq34bih"/><path class="uzc1k5bdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:autotune" {...props}></Icon>
<style>
:global(.ghqq34bih) {
  d: path("M3 2.5V21h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uzc1k5bdu) {
  d: path("M6 13c1.5-6 4-6 5.5-1c.75 2.5 1.5 3 2.5 3h2.5V8h5");
}

</style>
