<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="do3pmcccq"/><path class="os6wc3b0l"/><path class="p9731tb5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:event-stream" {...props}></Icon>
<style>
:global(.do3pmcccq) {
  d: path("M12 2v1m0 3.5V8m0 3.5V13m0 3.5V18m0 3.5v.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.os6wc3b0l) {
  fill: currentColor;
  d: path("M10.75 4.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

:global(.p9731tb5n) {
  d: path("M10.75 9.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m0 5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
