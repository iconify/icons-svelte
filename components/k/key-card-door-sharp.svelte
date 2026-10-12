<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v2l0w2bvw"/><path class="u_p9z_fnh"/><path class="myyoyjbzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:key-card-door-sharp" {...props}></Icon>
<style>
:global(.myyoyjbzu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.69 12.06L13.621 14l-1.931 1.94m1.6-5.48a5 5 0 0 1 0 7.08");
}

:global(.u_p9z_fnh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 14h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.v2l0w2bvw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h11.5v18.5H6.25zm0 4h11.5");
}

</style>
