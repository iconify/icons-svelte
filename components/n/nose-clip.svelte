<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pdk93gbge"/><path class="gt_cb9bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:nose-clip" {...props}></Icon>
<style>
:global(.gt_cb9bxb) {
  d: path("M7 18a1.75 2.75 0 1 0 3.5 0A1.75 2.75 0 1 0 7 18Zm6.5 0a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0Z");
}

:global(.pdk93gbge) {
  d: path("M8.75 15.25C6 12 5.5 4.5 12 4.5s6 7.5 3.25 10.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
