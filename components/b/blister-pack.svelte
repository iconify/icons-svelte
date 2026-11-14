<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kuknfnbhx"/><path class="iwt24bbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:blister-pack" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iwt24bbxv) {
  d: path("M6.5 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 1 2 2");
}

:global(.kuknfnbhx) {
  d: path("M8.375 2.5h7.25A4.375 4.375 0 0 1 20 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 17.125V6.875A4.375 4.375 0 0 1 8.375 2.5");
}

</style>
