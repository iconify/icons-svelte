<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="le70crjja"/><path class="ky1incdfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:car-electric-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.ky1incdfw) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 8l-3 3h4l-3 3m1 4H6a2 2 0 0 1-2-2v-6l2-4c.613-1.226 1.774-2 3-2h6c1.226 0 2.387.774 3 2l2 4v6a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 10h1m16 0h1");
}

:global(.le70crjja) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 16v-6l2-4c.569-1.137 1.695-1.999 3-2h6c1.305.001 2.431.863 3 2l2 4v6a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2");
}

</style>
