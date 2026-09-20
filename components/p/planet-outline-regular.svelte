<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rcb4z6b_d"/><path class="t4v1u1jek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:planet-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rcb4z6b_d) {
  d: path("M5 11a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.t4v1u1jek) {
  d: path("M2 13c4 5 16 5 20 0");
}

</style>
