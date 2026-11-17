<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t-7br09vh"/><path class="dh6mzjbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-off-duotone-sharp" {...props}></Icon>
<style>
:global(.dh6mzjbiu) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17H3V7h4m6 0h5v5m3-2v4M2 2l20 20");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.t-7br09vh) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 17H3V7h4ZM13 7h5v5Z");
}

</style>
