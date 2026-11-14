<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojxo4n94s"/><path class="w54u42bbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pool-rack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ojxo4n94s) {
  d: path("M7.04 19.5h9.92a2.625 2.625 0 0 0 2.275-3.935l-4.96-8.614a2.625 2.625 0 0 0-4.55 0l-4.96 8.614A2.625 2.625 0 0 0 7.04 19.5");
}

:global(.w54u42bbs) {
  d: path("M7.75 15.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10.5 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
