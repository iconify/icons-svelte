<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lc0ypcbre"/><path class="n0u1uccdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caravan-duotone-sharp" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lc0ypcbre) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 18V5h14v13h-5a1.999 1.999 0 0 0-3-1.732c-.619.357-1 1.017-1 1.732Z");
}

:global(.n0u1uccdw) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 18H3V5h14v13h-5M7 9h6v4H7Zm1 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9-3h4");
}

</style>
