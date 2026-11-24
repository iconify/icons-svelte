<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bs48nipqm"/><path class="e2_w36bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-edit-corner-duotone-sharp" {...props}></Icon>
<style>
:global(.bs48nipqm) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 9H9v10H3V5h18Zm-8 12v-3l5-5l3 3l-5 5Z");
}

:global(.e2_w36bgc) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9V5H3v14h6M3 9h18m-8 12v-3l5-5l3 3l-5 5Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
