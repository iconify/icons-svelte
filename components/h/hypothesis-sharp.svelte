<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dm6066bor"/><path class="nsi2xwbio"/><path class="bvog_2vkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hypothesis-sharp" {...props}></Icon>
<style>
:global(.bvog_2vkr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01M4.5 20.25h.01");
}

:global(.dm6066bor) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 16.85a4 4 0 0 1-.55-7.96A5.75 5.75 0 0 1 16.85 7.5a4.5 4.5 0 0 1-.6 9.35Z");
}

:global(.nsi2xwbio) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 9.25a1.9 1.9 0 1 1 2.6 1.75l-.85.34v1.16");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
