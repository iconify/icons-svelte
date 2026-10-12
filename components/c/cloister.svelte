<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xsxnl-bkf"/><rect class="xdzl73b3t"/><path class="rmsdscb8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cloister" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rmsdscb8q) {
  d: path("M12 15v6.25");
}

:global(.xdzl73b3t) {
  width: 2.5px;
  height: 5.5px;
  x: 10.75px;
  y: 9.5px;
  rx: 1.25px;
}

:global(.xsxnl-bkf) {
  d: path("M2.75 21.25V7L8.5 9.5V18A1.75 1.75 0 0 0 5 18v3.25Zm18.5 0V7L15.5 9.5V18a1.75 1.75 0 0 1 3.5 0v3.25Z");
}

</style>
