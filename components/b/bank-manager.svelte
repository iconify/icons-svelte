<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wnv98nbvk"/><path class="olzkx_9do"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bank-manager" {...props}></Icon>
<style>
:global(.olzkx_9do) {
  d: path("M11 13.5h2l-.25 1.5L14 19.5l-2 2l-2-2l1.25-4.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wnv98nbvk) {
  d: path("M8.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-5 15c0-5 3.5-8 8.5-8s8.5 3 8.5 8");
}

</style>
