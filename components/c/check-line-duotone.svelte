<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wudpi-b1g"/><path class="lpz3vpbnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:check-line-duotone" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lpz3vpbnp) {
  d: path("M5 13L9 17");
}

:global(.wudpi-b1g) {
  d: path("M9 17L19 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
