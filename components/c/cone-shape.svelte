<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jpat6ejll"/><path class="rzn19kbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cone-shape" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jpat6ejll) {
  d: path("M12 3.5L19 18c0 1.75-3.25 3-7 3s-7-1.25-7-3Z");
}

:global(.rzn19kbdn) {
  d: path("M5 18c0-1.5 3.25-2.75 7-2.75s7 1.25 7 2.75");
}

</style>
