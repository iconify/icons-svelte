<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujw9c-ben"/><path class="c8p2edctq"/><path class="kzxwn_jgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rock-outline-regular" {...props}></Icon>
<style>
:global(.c8p2edctq) {
  d: path("m9 6 6 6h6");
}

:global(.kzxwn_jgc) {
  d: path("M15 12v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ujw9c-ben) {
  d: path("m3 12 6 -6h6l6 6 -6 6H9Z");
}

</style>
