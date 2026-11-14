<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bidnqubik"/><path class="jkvcz3vir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:aid-convoy" {...props}></Icon>
<style>
:global(.bidnqubik) {
  d: path("M2.5 14V7a1 1 0 0 1 1-1h4v3H9l1.5 1.75V14Zm11 0V7a1 1 0 0 1 1-1h4v3H20l1.5 1.75V14Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jkvcz3vir) {
  d: path("M3 15.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.75 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5.25 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
