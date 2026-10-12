<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ayv-53bwz"/><path class="su7wuov-l"/><path class="vxh593bgm"/><circle class="eav5g_b0l"/><circle class="y9y1r0c9o"/><path class="z9yu7jb1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gimbal-stabilizer-sharp" {...props}></Icon>
<style>
:global(.ayv-53bwz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75h13.5v5H7.75z");
}

:global(.eav5g_b0l) {
  cx: 4.5px;
  cy: 5.25px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.su7wuov-l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 5.25h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vxh593bgm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 11.5h-6V6.75M6 5.25h1.75");
}

:global(.y9y1r0c9o) {
  cx: 12px;
  cy: 11.5px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z9yu7jb1w) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 14h4v7.25h-4z");
}

</style>
