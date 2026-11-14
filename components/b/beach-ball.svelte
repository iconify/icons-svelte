<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lx9cp9byq"/><path class="u6rng2b-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beach-ball" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lx9cp9byq) {
  d: path("M5 9.75a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

:global(.u6rng2b-y) {
  d: path("M12 2.75c-3.5 3-3.5 11 0 14m0-14c3.5 3 3.5 11 0 14m-9 4q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
