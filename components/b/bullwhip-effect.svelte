<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttsfjubit"/><path class="tx7vg9nnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bullwhip-effect" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ttsfjubit) {
  d: path("M2.5 2.5v19h19");
}

:global(.tx7vg9nnx) {
  d: path("M5.5 11L8 9.5l2.5 3.5l3-6l3 10L20 4");
}

</style>
