<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gmikdxb7d"/><path class="mbesug8jl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:carnival-mask" {...props}></Icon>
<style>
:global(.gmikdxb7d) {
  d: path("M2.5 6C6 5 9 6 12 7.5C15 6 18 5 21.5 6c0 4-2.5 7.5-6 7.5c-2 0-2.75-1.5-3.5-2.5c-.75 1-1.5 2.5-3.5 2.5c-3.5 0-6-3.5-6-7.5Zm15.75 6.75l1.5 7.75");
}

:global(.mbesug8jl) {
  d: path("M5.75 9a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Zm8 0a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
