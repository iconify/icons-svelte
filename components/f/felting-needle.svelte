<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbdw9srqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:felting-needle" {...props}></Icon>
<style>
:global(.pbdw9srqc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5C2 17 5 13.5 8 15c1-3 6-3 6.5.5c2.5 0 3 5 .5 5ZM21 3L10.5 15.5");
}

</style>
