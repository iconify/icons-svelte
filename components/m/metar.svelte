<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hdpealb0k"/><path class="b8evbbbwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:metar" {...props}></Icon>
<style>
:global(.b8evbbbwm) {
  d: path("M15.25 21.5A2.25 2.25 0 0 1 15 17a2.75 2.75 0 0 1 5 .75a1.9 1.9 0 0 1 0 3.75Z");
}

:global(.hdpealb0k) {
  d: path("M10.6 21.5H4.5v-19h15v10.8M8 7h8m-8 4h8m-8 4h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
