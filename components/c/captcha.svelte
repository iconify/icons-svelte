<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="poz_fvbbz"/><path class="mrwnyta9z"/><path class="ytjr9nb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:captcha" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mrwnyta9z) {
  d: path("M7.25 9h2.5a1.75 1.75 0 0 1 1.75 1.75v2.5A1.75 1.75 0 0 1 9.75 15h-2.5a1.75 1.75 0 0 1-1.75-1.75v-2.5A1.75 1.75 0 0 1 7.25 9");
}

:global(.poz_fvbbz) {
  d: path("M6.875 5h10.25A4.375 4.375 0 0 1 21.5 9.375v5.25A4.375 4.375 0 0 1 17.125 19H6.875A4.375 4.375 0 0 1 2.5 14.625v-5.25A4.375 4.375 0 0 1 6.875 5");
}

:global(.ytjr9nb1j) {
  d: path("M6.75 12L8 13.25l2.25-2.5M14 12h4.5");
}

</style>
