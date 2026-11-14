<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udfa5dztv"/><path class="wqmtfwbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:at-sign" {...props}></Icon>
<style>
:global(.udfa5dztv) {
  d: path("M8.25 12a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wqmtfwbjw) {
  d: path("M15.75 8.25v5.25a2.375 2.375 0 0 0 4.75 0V12a8.5 8.5 0 1 0-3.5 6.75");
}

</style>
