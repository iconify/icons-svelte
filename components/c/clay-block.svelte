<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nq9grwtwn"/><path class="absrzacth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clay-block" {...props}></Icon>
<style>
:global(.absrzacth) {
  d: path("M2.5 9H17v8m0-8l4.5-4.75M2 19.75h20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nq9grwtwn) {
  d: path("M2.5 9L7 4.25h14.5v8.25L17 17H2.5Z");
}

</style>
