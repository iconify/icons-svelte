<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f19qm5bcq"/><path class="xd3b4uwlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rotate-right-duocolor-sharp" {...props}></Icon>
<style>
:global(.f19qm5bcq) {
  stroke-opacity: 0.4;
  d: path("M12 6H5v4m4-7l3 3l-3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xd3b4uwlw) {
  d: path("M5 14v6h14V6h-3");
}

</style>
