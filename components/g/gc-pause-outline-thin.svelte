<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7pgrp-wx"/><path class="wp75hkmty"/><path class="rutulxlvn"/><path class="e69i7fcek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gc-pause-outline-thin" {...props}></Icon>
<style>
:global(.e69i7fcek) {
  d: path("M17 12h5");
}

:global(.e7pgrp-wx) {
  d: path("M2 12h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rutulxlvn) {
  d: path("M14 7v10");
}

:global(.wp75hkmty) {
  d: path("M11 7v10");
}

</style>
