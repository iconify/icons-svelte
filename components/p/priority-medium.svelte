<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nfo0c4boq"/><path class="pnimyfb6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:priority-medium" {...props}></Icon>
<style>
:global(.nfo0c4boq) {
  fill: currentColor;
  d: path("M2.5 14H7v6H2.5Zm7.25-5h4.5v11h-4.5Z");
}

:global(.pnimyfb6u) {
  d: path("M17 4h4.5v16H17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
