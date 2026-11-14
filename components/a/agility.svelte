<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v2qaygb1r"/><path class="g5vumqbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agility" {...props}></Icon>
<style>
:global(.g5vumqbqx) {
  d: path("M15.5 6.5H20V11M2.5 6.5H6m-3.5 4h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v2qaygb1r) {
  d: path("m4 17.5l6-8l3 4l7-7");
}

</style>
