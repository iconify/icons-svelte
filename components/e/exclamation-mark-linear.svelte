<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tm82ehw_u"/><path class="azdzsac_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exclamation-mark-linear" {...props}></Icon>
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

:global(.tm82ehw_u) {
  d: path("M12 2V15.3333");
}

</style>
