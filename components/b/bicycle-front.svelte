<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dexf-xyin"/><path class="ds-axhblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bicycle-front" {...props}></Icon>
<style>
:global(.dexf-xyin) {
  d: path("M10 15.75a2 5.75 0 1 0 4 0a2 5.75 0 1 0-4 0");
}

:global(.ds-axhblu) {
  d: path("M7.25 15.5V7h9.5v8.5M12 4.25V7M2.5 2.75q1 1.5 2.5 1.5h14q1.5 0 2.5-1.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
