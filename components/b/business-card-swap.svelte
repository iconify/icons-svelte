<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="quk2js0hl"/><path class="f-56kqphr"/><path class="qykzcgbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:business-card-swap" {...props}></Icon>
<style>
:global(.f-56kqphr) {
  d: path("m17 9.75l2 2l2-2M8.75 18H7.5A2.5 2.5 0 0 1 5 15.5v-3.25");
}

:global(.quk2js0hl) {
  d: path("M2.5 2.5h10v7h-10Zm9 12h10v7h-10ZM15 6h1.5A2.5 2.5 0 0 1 19 8.5v3.25");
}

:global(.qykzcgbau) {
  d: path("m3 14.25l2-2l2 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
