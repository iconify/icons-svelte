<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="msqnovtqe"/><path class="vck1iacwt"/><path class="kq8xo7b0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:database-er" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kq8xo7b0j) {
  d: path("M3 9.5a5 2 0 0 0 10 0M8 16v2.5h7.75m2.625-3.25h.75a2.625 2.625 0 0 1 2.625 2.625v.75a2.625 2.625 0 0 1-2.625 2.625h-.75a2.625 2.625 0 0 1-2.625-2.625v-.75a2.625 2.625 0 0 1 2.625-2.625");
}

:global(.msqnovtqe) {
  d: path("M3 5a5 2 0 1 0 10 0A5 2 0 1 0 3 5");
}

:global(.vck1iacwt) {
  d: path("M3 5v9a5 2 0 0 0 10 0V5");
}

</style>
