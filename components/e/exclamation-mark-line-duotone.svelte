<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xqplh-1nb"/><path class="azdzsac_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exclamation-mark-line-duotone" {...props}></Icon>
<style>
:global(.azdzsac_a) {
  stroke-linejoin: round;
  d: path("M12 22H12.0001");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xqplh-1nb) {
  d: path("M12 2V15.3333");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
