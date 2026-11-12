<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="r0xhknb7f"/><path class="mj_6ev9oe"/><path class="k9eq3dbyp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-slash-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k9eq3dbyp) {
  d: path("M9.73242 13.2678L11.5002 11.5L13.268 9.73223");
}

:global(.mj_6ev9oe) {
  d: path("M20 20L22 22");
}

:global(.r0xhknb7f) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
