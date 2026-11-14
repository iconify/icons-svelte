<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zpc0mrzbr"/><path class="nasrfzbjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:moon-crescent" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nasrfzbjy) {
  d: path("M9.25 3.5A9.5 9.5 0 0 0 20.5 14.75");
}

:global(.zpc0mrzbr) {
  d: path("M20.5 14.75A9.25 9.25 0 1 1 9.25 3.5");
}

</style>
