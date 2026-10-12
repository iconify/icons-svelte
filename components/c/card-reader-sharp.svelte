<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ap41eacnp"/><path class="p1x7434yb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:card-reader-sharp" {...props}></Icon>
<style>
:global(.ap41eacnp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.25h4l.71.71l.58.58l.71.71v5.5h-7v-7.5zm-3.5 7.5h12v8h-12zm12 2h6.5v4h-6.5z");
}

:global(.p1x7434yb) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 15.75h.01m1.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
