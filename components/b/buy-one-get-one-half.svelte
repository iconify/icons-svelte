<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xp7b-ebfk"/><path class="dptv52egi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:buy-one-get-one-half" {...props}></Icon>
<style>
:global(.dptv52egi) {
  fill: currentColor;
  d: path("M13.5 18.5H21V11Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xp7b-ebfk) {
  d: path("M2.5 7H11v12H2.5ZM13 7h8.5v12H13ZM2.5 10H11m2 0h8.5");
}

</style>
