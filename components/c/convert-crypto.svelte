<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d6aam1rah"/><path class="e_6pypczm"/><path class="rmeuof7of"/><path class="mfq48mbqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:convert-crypto" {...props}></Icon>
<style>
:global(.d6aam1rah) {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

:global(.e_6pypczm) {
  d: path("M3.5 12A8.5 8.5 0 0 1 18 6");
}

:global(.mfq48mbqz) {
  d: path("M6 21.5V18h3.5");
}

:global(.rmeuof7of) {
  d: path("M18 2.5V6h-3.5m6 6A8.5 8.5 0 0 1 6 18");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
