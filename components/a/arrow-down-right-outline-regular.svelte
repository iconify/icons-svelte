<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="po51cnplk"/><path class="cejwj-bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-right-outline-regular" {...props}></Icon>
<style>
:global(.cejwj-bns) {
  d: path("M10 20h10V10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.po51cnplk) {
  d: path("m4 4 16 16");
}

</style>
