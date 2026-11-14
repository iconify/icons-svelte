<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bfv9hiq9m"/><path class="fs1q8-dbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:corner-up-left" {...props}></Icon>
<style>
:global(.bfv9hiq9m) {
  d: path("M19.5 19.5V13A3.5 3.5 0 0 0 16 9.5H4.5");
}

:global(.fs1q8-dbp) {
  d: path("m9.5 4.5l-5 5l5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
