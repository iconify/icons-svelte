<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uw_p-4b4x"/><path class="c-grx3b4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:heart-rate-variability" {...props}></Icon>
<style>
:global(.c-grx3b4o) {
  d: path("M6.5 11.5H9L10.5 9l2.5 6l1.5-3.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uw_p-4b4x) {
  d: path("M12 20c-7-4.5-9.5-8.5-9.5-11.5s2.25-5 4.75-5c2 0 3.75 1.25 4.75 3c1-1.75 2.75-3 4.75-3c2.5 0 4.75 2 4.75 5S19 15.5 12 20Z");
}

</style>
