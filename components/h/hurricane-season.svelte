<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d925dqbjv"/><path class="pw_9hdy_j"/><path class="fd3515rqr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hurricane-season" {...props}></Icon>
<style>
:global(.d925dqbjv) {
  d: path("M3 4.5h18V21H3Zm5-2v4m8-4v4");
}

:global(.fd3515rqr) {
  d: path("M10 13.5c0-3 2.25-4.25 5-4m-1 4c0 3-2.25 4.25-5 4");
}

:global(.pw_9hdy_j) {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
