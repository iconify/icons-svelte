<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pfg7ibsmz"/><path class="d0rc8obax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:certificate" {...props}></Icon>
<style>
:global(.d0rc8obax) {
  d: path("M13 10.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m1.25 2.5l-.75 7.25m3.75-7.25L18 20.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pfg7ibsmz) {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5V14a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 14V7.5A3.5 3.5 0 0 1 6 4m0 4.5h5M6 12h3.5");
}

</style>
