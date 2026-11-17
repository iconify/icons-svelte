<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nuvo05bir"/><path class="nb-6bsb6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:glass-water-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.nb-6bsb6r) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18 12l-.802 7.22A2 2 0 0 1 15.21 21H8.79a2 2 0 0 1-1.988-1.78L5.221 4.989A1.79 1.79 0 0 1 7 3h10a1.79 1.79 0 0 1 1.78 1.988zM6 12h12");
}

:global(.nuvo05bir) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 12h12l-.802 7.221A2 2 0 0 1 15.21 21H8.79a2 2 0 0 1-1.988-1.779Z");
}

</style>
