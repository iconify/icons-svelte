<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="buwxn3cmu"/><path class="joc_c_b3v"/><path class="sokq-oczf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-flow" {...props}></Icon>
<style>
:global(.buwxn3cmu) {
  d: path("M2.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m14 7.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-14 7.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M8 4.75h6.5c2.5 0 4.5 1.5 4.5 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.joc_c_b3v) {
  d: path("M17.25 7L19 8.75L20.75 7M19 15.25c0 2.5-2 4-4.5 4H8");
}

:global(.sokq-oczf) {
  d: path("M9.75 17.5L8 19.25L9.75 21");
}

</style>
