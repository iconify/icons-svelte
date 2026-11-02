<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ru787lbrb"/><path class="vmuvplbiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:puzzle-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ru787lbrb) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 7v5a2.235 2.235 0 1 0 0 4v5H7v-5a2.235 2.235 0 1 1 0-4V7h5a2.235 2.235 0 1 1 4 0Z");
}

:global(.vmuvplbiq) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 7h5v5a2.236 2.236 0 1 0 0 4v5H7v-5a2.236 2.236 0 1 1 0-4V7h5a2.236 2.236 0 1 1 4 0");
}

</style>
