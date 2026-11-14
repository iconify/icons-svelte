<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e6cvfq3zf"/><path class="pflefjb-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrive-home" {...props}></Icon>
<style>
:global(.e6cvfq3zf) {
  d: path("M10 12.5V11l5.5-5l5.5 5v9H10v-1.5m-7.5-3h11");
}

:global(.pflefjb-l) {
  d: path("m11.25 13.25l2.25 2.25l-2.25 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
