<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mhkuqgz9x"/><path class="eooy75brd"/><path class="hxyabovjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:double-espresso" {...props}></Icon>
<style>
:global(.eooy75brd) {
  d: path("M8.75 9H9a1.5 1.5 0 0 1 0 3h-.75m5-4.5h5.5v3a2.75 2.75 0 0 1-5.5 0Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxyabovjh) {
  d: path("M18.75 9H19a1.5 1.5 0 0 1 0 3h-.75m-15.5 4h18.5");
}

:global(.mhkuqgz9x) {
  d: path("M3.25 7.5h5.5v3a2.75 2.75 0 0 1-5.5 0Z");
}

</style>
