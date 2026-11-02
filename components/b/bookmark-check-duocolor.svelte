<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu_mukbdk"/><path class="f8k7zkb6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-check-duocolor" {...props}></Icon>
<style>
:global(.f8k7zkb6h) {
  d: path("M12 4h4a2 2 0 0 1 2 2v12c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V6a2 2 0 0 1 2-2z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vu_mukbdk) {
  stroke-opacity: 0.4;
  d: path("m9 10l2 2l4-4");
}

</style>
