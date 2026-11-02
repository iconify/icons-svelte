<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zz-38cczo"/><path class="ifdryrb5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-pyramid-duocolor-sharp" {...props}></Icon>
<style>
:global(.ifdryrb5s) {
  d: path("m16 11l5 10H3l9-18z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zz-38cczo) {
  stroke-opacity: 0.4;
  d: path("M9 9h6m-9 6h12");
}

</style>
