<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="nd9i8bcij"/><path class="mc8uz8lrh"/><path class="pj2nckb9w"/><path class="f8f9z_b2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:juicer-sharp" {...props}></Icon>
<style>
:global(.f8f9z_b2y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.25h5.25V11m-1.75 3h4.5l-.05.75l-.4 5.75l-.05.75H16.5l-.05-.75l-.4-5.75L16 14z");
}

:global(.mc8uz8lrh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5.75a2.25 2.25 0 1 1 0 4.5a2.25 2.25 0 1 1 0-4.5Z");
}

:global(.nd9i8bcij) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h10v18.5h-10z");
}

:global(.pj2nckb9w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 16.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
