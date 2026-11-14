<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8t0v3ktt"/><path class="lqsvcdcna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:aisle-sign" {...props}></Icon>
<style>
:global(.l8t0v3ktt) {
  d: path("M3 9h18v11H3Zm-.5-5.5h19M7 3.5V9m10-5.5V9M6.5 14.5h11");
}

:global(.lqsvcdcna) {
  d: path("m14.5 11.75l3 2.75l-3 2.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
