<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y1ek1lbvh"/><path class="aefj23ssx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:return-to-work" {...props}></Icon>
<style>
:global(.aefj23ssx) {
  d: path("m8 10l2 2l2-2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y1ek1lbvh) {
  d: path("M14 4.5h5V12h-5Zm-1 10.25h7m-3.5 0v4.75m-3 0h6m-6 2.25h.01m5.99 0h.01M3 19.5v-11a3.5 3.5 0 0 1 7 0V12");
}

</style>
