<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="st_pmyb4h"/><path class="k0i0ytbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-mall" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0i0ytbox) {
  d: path("M9 11V6a3 3 0 0 1 6 0v5");
}

:global(.st_pmyb4h) {
  d: path("M4.5 7.5h15v12a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2Z");
}

</style>
