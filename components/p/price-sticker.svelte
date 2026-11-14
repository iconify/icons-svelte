<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-rxsdbeq"/><path class="vg8r6tbjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:price-sticker" {...props}></Icon>
<style>
:global(.h-rxsdbeq) {
  d: path("M21.5 12A9.5 9.5 0 1 1 12 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vg8r6tbjz) {
  d: path("M12 2.5c-.25 5.5 3.75 9.75 9.5 9.5M12 2.5l9.5 9.5M7 12h4m-4 3.5h6");
}

</style>
