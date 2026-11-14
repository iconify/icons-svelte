<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tkb58bblb"/><path class="mx0fg5k1l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:in-stock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mx0fg5k1l) {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v2.75M14.75 18l2 2L21 15.75");
}

:global(.tkb58bblb) {
  d: path("M12 2.5L20.5 7v5.25H14a2 2 0 0 0-2 2v7.25L3.5 17V7Z");
}

</style>
