<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zk06y4wct"/><path class="mmh5q-f0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:city-bike" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mmh5q-f0k) {
  d: path("M6 15.5h5.5q1.5-7 5-7.5l1.5 7.5M16.5 8l-.25-2.5h2.5m-7.25 10l-1-7.5M9 8h3m5 2a5.5 5.5 0 0 1 4.25 1");
}

:global(.zk06y4wct) {
  d: path("M2.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m12 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m-12-4.5a5.5 5.5 0 0 1 5-.75");
}

</style>
