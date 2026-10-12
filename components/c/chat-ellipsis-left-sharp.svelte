<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jpcsitb_x"/><path class="maf5by7ww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chat-ellipsis-left-sharp" {...props}></Icon>
<style>
:global(.jpcsitb_x) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85h-1.616l-1.484-.5L4.6 20l-1.57.523l.67-1.473l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85Z");
}

:global(.maf5by7ww) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 11.1h.01m3.99 0h.01m3.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
