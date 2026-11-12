<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wx9p5uqgi"/><path class="v2_l12bpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-clock-corner-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v2_l12bpv) {
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4");
}

:global(.wx9p5uqgi) {
  stroke-opacity: 0.4;
  d: path("M12 17a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
