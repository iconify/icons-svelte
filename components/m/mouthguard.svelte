<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rqmkh2bii"/><path class="qaxgs-v7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mouthguard" {...props}></Icon>
<style>
:global(.qaxgs-v7v) {
  d: path("M6.5 12c1 2 3 2.75 5.5 2.75S16.5 14 17.5 12");
}

:global(.rqmkh2bii) {
  d: path("M3 9c0 6 4 9 9 9s9-3 9-9a2.25 2.25 0 0 0-4.5 0A2.25 2.25 0 0 0 12 9a2.25 2.25 0 0 0-4.5 0A2.25 2.25 0 0 0 3 9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
