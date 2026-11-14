<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7eay_aag"/><path class="ejkj6th1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:calendar-shared" {...props}></Icon>
<style>
:global(.ejkj6th1k) {
  d: path("M16.25 15.5h4.25v4.25");
}

:global(.t7eay_aag) {
  d: path("M11.1 21H3V4.5h17v7.6M3 9.5h17m-12.5-7v4m8-4v4M15 21l5.25-5.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
