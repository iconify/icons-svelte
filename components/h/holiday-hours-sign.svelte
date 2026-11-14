<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kosg3lbhc"/><path class="w83jmcbzu"/><path class="j4tjirbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:holiday-hours-sign" {...props}></Icon>
<style>
:global(.j4tjirbbw) {
  d: path("M12 12.25v2h1.5");
}

:global(.kosg3lbhc) {
  d: path("M3 3h18M7 3v4m10-4v4M3 7h18v14.5H3Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w83jmcbzu) {
  d: path("M7.75 14.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

</style>
