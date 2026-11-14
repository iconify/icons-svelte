<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q4o2fgtps"/><path class="yvrg0zbqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:atm-contactless" {...props}></Icon>
<style>
:global(.q4o2fgtps) {
  d: path("M14.8 21.5H4v-19h16v8.3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yvrg0zbqd) {
  d: path("M7 5h10v6H7Zm-.5 8.75h9.1m-8.85 3.5h.01m2.49 0h.01m2.49 0h.01m3.49.75h.01m1.935-1.945a2.75 2.75 0 0 1 0 3.89m2.268-5.48a5.5 5.5 0 0 1 0 7.07");
}

</style>
