<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="b0hhfnb7m"/><path class="hqn_f6b_h"/><circle class="zhtdkvboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:d-pad-sharp" {...props}></Icon>
<style>
:global(.b0hhfnb7m) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h5.25v6h6v6.5h-6v6h-6.5v-6h-6v-6.5h6v-6z");
}

:global(.hqn_f6b_h) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01M18.25 12h.01M12 18.25h.01M5.75 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zhtdkvboy) {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
