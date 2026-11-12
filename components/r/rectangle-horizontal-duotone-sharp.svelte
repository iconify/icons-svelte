<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a5pufybtq"/><path class="qtw08wbbh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rectangle-horizontal-duotone-sharp" {...props}></Icon>
<style>
:global(.a5pufybtq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 7h18v10H3Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.qtw08wbbh) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7h18v10H3Z");
}

</style>
