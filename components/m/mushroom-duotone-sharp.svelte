<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="agbiupgjg"/><path class="e7_jnabwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mushroom-duotone-sharp" {...props}></Icon>
<style>
:global(.agbiupgjg) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 11a8 8 0 0 1 16 0h-6v8a2 2 0 1 1-4 0v-8Z");
}

:global(.e7_jnabwg) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11a8 8 0 1 1 16 0Zm6 0v8a2 2 0 1 0 4 0v-8");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
