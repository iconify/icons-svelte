<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b9lwcdbld"/><path class="h9a4pqbei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-horizontal-duotone-round" {...props}></Icon>
<style>
:global(.b9lwcdbld) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 9a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.h9a4pqbei) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9a3 3 0 0 1 6 0v6a3 3 0 0 1-6 0ZM4 3v18M20 3v18");
}

</style>
