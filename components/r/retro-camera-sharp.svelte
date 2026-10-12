<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="db_vo49wb"/><path class="ueu0wwb-p"/><path class="gvxi5pmpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:retro-camera-sharp" {...props}></Icon>
<style>
:global(.db_vo49wb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25h12.5V21H2.75zm2.25 0v-2.5h4v2.5Z");
}

:global(.gvxi5pmpg) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 4h.01");
}

:global(.ueu0wwb-p) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 11.75a3.25 3.25 0 1 1 0 6.5a3.25 3.25 0 0 1 0-6.5Zm4.5-5v2.5M10.75 4a2.75 2.75 0 0 0 5.5 0");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
