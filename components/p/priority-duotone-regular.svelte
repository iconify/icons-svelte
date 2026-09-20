<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="he5ikxbaq"/><path class="wc9wh3b0p"/><path class="ckawxab4i"/><path class="egu9ezovw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:priority-duotone-regular" {...props}></Icon>
<style>
:global(.ckawxab4i) {
  d: path("m4 11 8 -8 8 8");
}

:global(.egu9ezovw) {
  d: path("m4 20 8 -8 8 8");
}

:global(.he5ikxbaq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wc9wh3b0p) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 20 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
