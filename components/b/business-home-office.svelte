<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bsq5xgbnw"/><path class="gvi7lev8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-home-office" {...props}></Icon>
<style>
:global(.bsq5xgbnw) {
  d: path("M3.5 21V10L12 2.5l8.5 7.5v11");
}

:global(.gvi7lev8b) {
  d: path("M8 9.5h8V15H8Zm4 5.5v3m-5.75 0h11.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
