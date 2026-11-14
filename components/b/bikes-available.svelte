<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cllub2yjr"/><path class="twkdnqbru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bikes-available" {...props}></Icon>
<style>
:global(.cllub2yjr) {
  d: path("M3 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m9 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.twkdnqbru) {
  d: path("M6.5 11H10l3.5-6l2 6M10 11L8.75 5m-1.5 0h3m3.25 0L13 3.5h2.5M14.75 18l2 2L21 15.75");
}

</style>
