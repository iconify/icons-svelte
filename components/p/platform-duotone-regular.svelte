<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="klh0dobdz"/><path class="b7j1iitps"/><path class="tg5bh2bez"/><path class="mqtixbwqo"/><path class="a9nj5hbth"/><path class="ils7yp4cg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:platform-duotone-regular" {...props}></Icon>
<style>
:global(.a9nj5hbth) {
  d: path("M4 11h16");
}

:global(.b7j1iitps) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ils7yp4cg) {
  d: path("M2 16h20");
}

:global(.klh0dobdz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tg5bh2bez) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
