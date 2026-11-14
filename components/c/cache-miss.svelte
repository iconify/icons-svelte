<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ap2347yrn"/><path class="k51mqjbge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cache-miss" {...props}></Icon>
<style>
:global(.ap2347yrn) {
  d: path("M13.71 17.895L10.5 19.5l-8-4v-9l8-4l8 4v6.556");
}

:global(.k51mqjbge) {
  d: path("m2.5 6.5l8 4l8-4m-8 4v9m-4-15l8 4m0 6L21 21m0-6.5L14.5 21");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
