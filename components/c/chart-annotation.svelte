<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n4-cnub9n"/><path class="naxuihbbe"/><path class="pt9utpz-k"/><path class="gdq1qkwik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-annotation" {...props}></Icon>
<style>
:global(.gdq1qkwik) {
  d: path("M18.75 2.5v2.75h2.75M15 7h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n4-cnub9n) {
  d: path("m2.5 19.5l3-4.5L8 10.5l3.5 6L15 14l6.5 4");
}

:global(.naxuihbbe) {
  fill: currentColor;
  d: path("M6.5 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.pt9utpz-k) {
  d: path("m9.5 9.5l3-2m.5-5h5.75l2.75 2.75V10H13Z");
}

</style>
