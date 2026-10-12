<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uvtpgvbkd"/><path class="lqh2nyb8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:milk-can" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lqh2nyb8m) {
  d: path("M9 5.75h6V9l2.75 2.5v8A1.75 1.75 0 0 1 16 21.25H8a1.75 1.75 0 0 1-1.75-1.75v-8L9 9Zm-.5 9.75h7m-9.25-3.25H4.5a1.5 1.5 0 0 0 0 3h1.75m11.5-3h1.75a1.5 1.5 0 0 1 0 3h-1.75");
}

:global(.uvtpgvbkd) {
  width: 7.5px;
  height: 2.5px;
  x: 8.25px;
  y: 3.25px;
  rx: 1px;
}

</style>
