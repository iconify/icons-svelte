<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bf2gb8u_p"/><path class="exzgiybys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-duotone-round" {...props}></Icon>
<style>
:global(.bf2gb8u_p) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 3h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5");
}

:global(.exzgiybys) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 17c-.502.227-1.413 0-2 0H8a4 4 0 0 1-4-4V8c0-1.36.963-2.277 2-3m5-1h5a4 4 0 0 1 4 4v5M9 20h6M3 2l19 19");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
