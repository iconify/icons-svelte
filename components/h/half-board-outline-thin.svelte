<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2nbo7bgf"/><path class="l8dn9jbyp"/><path class="tla8vyn6c"/><path class="olqfcgidt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:half-board-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2nbo7bgf) {
  d: path("M4 15a8 8 0 0 1 16 0");
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.olqfcgidt) {
  d: path("M6 19h12");
}

:global(.tla8vyn6c) {
  d: path("M12 7v8");
}

</style>
