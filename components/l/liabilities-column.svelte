<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vl3pdebcp"/><path class="v6tvnkypj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:liabilities-column" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6tvnkypj) {
  fill: currentColor;
  d: path("M9 13.5h6a1.75 1.75 0 0 1 1.75 1.75V17A1.75 1.75 0 0 1 15 18.75H9A1.75 1.75 0 0 1 7.25 17v-1.75A1.75 1.75 0 0 1 9 13.5");
}

:global(.vl3pdebcp) {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5M8 6.5h8M8 10h5.5");
}

</style>
