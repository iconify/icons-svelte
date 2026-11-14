<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck6lwowvk"/><path class="v_zz76tcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-salad" {...props}></Icon>
<style>
:global(.ck6lwowvk) {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v_zz76tcf) {
  d: path("M7 11h10a5 5 0 0 1-10 0m3 0c0-3 2-4 4.5-4.25c.25 2.25-1 4.25-1.75 4.25");
}

</style>
