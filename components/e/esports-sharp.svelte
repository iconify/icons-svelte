<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gd_nsmbgo"/><path class="u_ss2j5bs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:esports-sharp" {...props}></Icon>
<style>
:global(.gd_nsmbgo) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 8.15v-4.9l.44.4l1.87 1.7l.44.4l.41-.44l1.93-2.12l.41-.44l.41.44l1.93 2.12l.41.44l.44-.4l1.87-1.7l.44-.4v5.5h-11zM8 11h8l2.945-.002l.505 2.902l.6 3.75a2.25 2.25 0 0 1-3.85 1.95L15 18.25H9L7.8 19.6a2.25 2.25 0 0 1-3.85-1.95l.6-3.75l.505-2.902zm-1.25 3.75h2.5M8 13.5V16");
}

:global(.u_ss2j5bs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 14.25h.01M16.75 16h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
