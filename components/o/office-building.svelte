<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f10_10mlr"/><path class="la4yn1b5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:office-building" {...props}></Icon>
<style>
:global(.f10_10mlr) {
  d: path("M6.75 21.25a2 2 0 0 1-2-2v-9.5a2 2 0 0 1 2-2h1.5v-2a2 2 0 0 1 2-2h3.5a2 2 0 0 1 2 2v2h1.5a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2Zm1.5-10v3.5m3.75-3.5v3.5m3.75-3.5v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.la4yn1b5e) {
  d: path("M10 21.25v-3h4v3");
}

</style>
