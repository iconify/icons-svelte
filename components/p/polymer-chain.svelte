<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6yvejbfl"/><path class="vagx1xboz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:polymer-chain" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6yvejbfl) {
  d: path("M3 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M16 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

:global(.vagx1xboz) {
  d: path("M6.25 15.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m6.5-6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
