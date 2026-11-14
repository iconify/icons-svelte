<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zremgbobi"/><path class="vt0mkkbui"/><path class="fsc3ttbcq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dermatoscope" {...props}></Icon>
<style>
:global(.fsc3ttbcq) {
  fill: currentColor;
  d: path("M8.25 9.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vt0mkkbui) {
  d: path("M5.5 9.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.zremgbobi) {
  d: path("M3 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm10.184 6.159l2.475-2.475l5.657 5.657l-2.475 2.475Z");
}

</style>
