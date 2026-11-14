<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lrigp0bmq"/><path class="qv75-lwvt"/><path class="dc6k549zu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coupon-stack" {...props}></Icon>
<style>
:global(.dc6k549zu) {
  d: path("M8.5 6h13v7.5M6 16.75h4");
}

:global(.lrigp0bmq) {
  d: path("M2.5 12h13v3a1.5 1.5 0 0 0 0 3v3.5h-13V18a1.5 1.5 0 0 0 0-3Z");
}

:global(.qv75-lwvt) {
  d: path("M5.5 9h13v7.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
