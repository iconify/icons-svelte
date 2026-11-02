<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qpf1wob0y"/><path class="cy58lm8nd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-open-duocolor-sharp" {...props}></Icon>
<style>
:global(.cy58lm8nd) {
  d: path("m5 20l3-9h13l-3 9z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qpf1wob0y) {
  stroke-opacity: 0.4;
  d: path("M19 11V6h-7l-2-2H3v16h2");
}

</style>
