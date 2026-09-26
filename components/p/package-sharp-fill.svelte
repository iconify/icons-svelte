<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g5-8adpwj"/><path class="fajy6kjai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-sharp-fill" {...props}></Icon>
<style>
:global(.fajy6kjai) {
  d: path("M2 6.8477L12 12M12 12L22 6.8477M12 12L12 22M7 4.4239L17 9.4239M12 2L22 6.8477L22 17.1523L12 22L2 17.1523L2 6.8477L12 2Z");
}

:global(.g5-8adpwj) {
  fill: currentColor;
  d: path("M22 6.8477L22 17.1523L12 22L2 17.1523L2 6.8477L12 12L22 6.8477Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
