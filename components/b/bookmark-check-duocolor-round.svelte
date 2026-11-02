<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu_mukbdk"/><path class="mt-25jbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-check-duocolor-round" {...props}></Icon>
<style>
:global(.mt-25jbdd) {
  d: path("M12 4h2a4 4 0 0 1 4 4v10c0 .855-1.718.855-3 0l-3-2l-3 2c-1.282.855-3 .855-3 0V8a4 4 0 0 1 4-4z");
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
