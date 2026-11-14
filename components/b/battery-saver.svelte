<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ub29l-bqr"/><path class="nawkhbc0k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:battery-saver" {...props}></Icon>
<style>
:global(.nawkhbc0k) {
  d: path("M7 14.5c0-3 2.25-5 7-5c0 3-2 5-7 5Z");
}

:global(.ub29l-bqr) {
  d: path("M2.5 7H19v10H2.5Zm19 3.5v3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
