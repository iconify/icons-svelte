<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jwfkkiwcy"/><path class="sref4lrmd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:marker-numbered" {...props}></Icon>
<style>
:global(.jwfkkiwcy) {
  d: path("M12 21.5C10.5 20 4.5 14.75 4.5 9.75a7.5 7.5 0 0 1 15 0c0 5-6 10.25-7.5 11.75Z");
}

:global(.sref4lrmd) {
  d: path("m10.25 8.25l2.25-1.5v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
