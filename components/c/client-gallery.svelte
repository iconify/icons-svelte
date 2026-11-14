<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bvl6rb0lu"/><path class="dvyxcjmkp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:client-gallery" {...props}></Icon>
<style>
:global(.bvl6rb0lu) {
  d: path("M13.4 17H2.5V3.5h18v8.6m-9 4.9v3.5m-3.5 0h3.6");
}

:global(.dvyxcjmkp) {
  d: path("m6 14l3.5-4.5l3 3l2-2L16 12m-1 9l5.25-5.25m-4-.25h4.25v4.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
