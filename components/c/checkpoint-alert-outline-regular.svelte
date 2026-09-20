<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="mhnr27bap"/><path class="so0bhmbof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-alert-outline-regular" {...props}></Icon>
<style>
:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.mhnr27bap) {
  d: path("M12 7v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.so0bhmbof) {
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
