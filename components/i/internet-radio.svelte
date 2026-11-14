<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m2e6babgl"/><path class="qi0zj4b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:internet-radio" {...props}></Icon>
<style>
:global(.m2e6babgl) {
  d: path("M2.5 10h19v11h-19Z");
}

:global(.qi0zj4b1t) {
  d: path("M5.5 15.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8-2h4m-4 4h4M9.845 7.242a3.5 3.5 0 0 1 4.31 0M7.05 5.05a7 7 0 0 1 9.9 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
