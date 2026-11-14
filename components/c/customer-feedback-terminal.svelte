<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ujo1b9iud"/><path class="gv37pg0xc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:customer-feedback-terminal" {...props}></Icon>
<style>
:global(.gv37pg0xc) {
  d: path("M9 10c1.5 2 4.5 2 6 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ujo1b9iud) {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v3.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 10.125v-3.25A4.375 4.375 0 0 1 8.875 2.5M12 14.5v7m-4 0h8M9.5 7h.01m4.99 0h.01");
}

</style>
