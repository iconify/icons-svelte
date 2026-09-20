<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aeyekmbly"/><path class="gnggw0bkv"/><path class="w3qv73i9r"/><path class="m7i92hb6f"/><path class="ve_htnadp"/><path class="b6rnmzrfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-scale-outline-regular" {...props}></Icon>
<style>
:global(.aeyekmbly) {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.b6rnmzrfq) {
  d: path("M19 11V5");
}

:global(.gnggw0bkv) {
  d: path("M7 19v-6");
}

:global(.m7i92hb6f) {
  d: path("M13 15V9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ve_htnadp) {
  d: path("M15 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.w3qv73i9r) {
  d: path("M9 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
