<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpq0qw7ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pitch-grass-stripes" {...props}></Icon>
<style>
:global(.jpq0qw7ou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.366 5h9.268a1.75 1.75 0 0 1 1.697 1.326l2.625 10.5A1.75 1.75 0 0 1 19.259 19H4.741a1.75 1.75 0 0 1-1.697-2.174l2.625-10.5A1.75 1.75 0 0 1 7.366 5M10 5L8.75 19M14 5l1.25 14");
}

</style>
