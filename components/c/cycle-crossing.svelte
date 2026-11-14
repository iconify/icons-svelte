<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tfvgaccjd"/><path class="s4mt855jw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cycle-crossing" {...props}></Icon>
<style>
:global(.s4mt855jw) {
  d: path("M7 10h4.5l3-5h-5l2 5m3-5l2.5 5m-2.5-5L14 3h2.25M6 17v4.5m6-4.5v4.5m6-4.5v4.5");
}

:global(.tfvgaccjd) {
  d: path("M3.75 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm10 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
