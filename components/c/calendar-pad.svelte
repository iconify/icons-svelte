<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hq5y3m-zt"/><path class="z_pm8i93a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-pad" {...props}></Icon>
<style>
:global(.hq5y3m-zt) {
  d: path("M4 6a1.5 1.5 0 0 1 1.5-1.5h13A1.5 1.5 0 0 1 20 6v7l-5 5H5.5A1.5 1.5 0 0 1 4 16.5Zm4.5-3.5v4m7-4v4M3 21h18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z_pm8i93a) {
  d: path("M20 13h-3.5a1.5 1.5 0 0 0-1.5 1.5V18M4 9.5h16");
}

</style>
