<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="addxdebsa"/><path class="g9zgykbnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:alarm-duotone" {...props}></Icon>
<style>
:global(.addxdebsa) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 13a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g9zgykbnm) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 0 0-16 0m8-4v4h4M3 6l3-3m12 0l3 3");
}

</style>
