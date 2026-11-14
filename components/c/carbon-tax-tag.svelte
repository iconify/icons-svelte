<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttsqbcboh"/><path class="scz8qzbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carbon-tax-tag" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.scz8qzbyp) {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.25 4.75l-5.5 5.75m-.5-5.25h.01m6.49 5h.01");
}

:global(.ttsqbcboh) {
  d: path("M12 2.5L19.5 8v11.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V8Z");
}

</style>
