<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srpel7lyw"/><path class="j14y-p33h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-to-line-duocolor-sharp" {...props}></Icon>
<style>
:global(.j14y-p33h) {
  d: path("m12 8l-4 4l4 4m-4-4h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.srpel7lyw) {
  stroke-opacity: 0.4;
  d: path("M4 6v12");
}

</style>
