<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dc4zz8uqj"/><path class="l-nerf3al"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.dc4zz8uqj) {
  stroke-opacity: 0.4;
  d: path("M21 10v4M2 2l20 20");
}

:global(.l-nerf3al) {
  d: path("M17 17H3V7h4m6 0h5v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
