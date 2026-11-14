<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n_d146n7o"/><path class="odu8bqrge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:clothes-hanger" {...props}></Icon>
<style>
:global(.n_d146n7o) {
  d: path("M9.75 7.5A2.25 2.25 0 1 1 12 9.75V12");
}

:global(.odu8bqrge) {
  d: path("m12 11.5l8 6.5H4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
