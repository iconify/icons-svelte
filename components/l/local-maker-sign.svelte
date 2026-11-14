<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fc58hkuzm"/><path class="swaykybso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:local-maker-sign" {...props}></Icon>
<style>
:global(.fc58hkuzm) {
  d: path("M12 21.5L5 13c-2-2.5-2-6.5 1-8.5C8.5 3 11 4 12 6c1-2 3.5-3 6-1.5c3 2 3 6 1 8.5Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.swaykybso) {
  d: path("M10 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
