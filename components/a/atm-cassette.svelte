<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hez-itsnf"/><path class="no642hb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:atm-cassette" {...props}></Icon>
<style>
:global(.hez-itsnf) {
  d: path("M2.5 12h19v9.5h-19ZM4 12V6.5a1 1 0 0 1 1-1h2.5m0 6.5V5a1 1 0 0 1 1-1H11m0 8V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

:global(.no642hb5j) {
  d: path("M13.5 7a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0ZM9 16.75h6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
