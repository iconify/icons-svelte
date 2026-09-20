<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z705ggbcg"/><path class="dx5s6zbrc"/><path class="yazo7scbq"/><path class="jnf_2db5t"/><path class="e0ead5bmw"/><path class="f8057zb1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:brightness-duotone-regular" {...props}></Icon>
<style>
:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.e0ead5bmw) {
  d: path("M3 12h3");
}

:global(.f8057zb1p) {
  d: path("M18 12h3");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

:global(.z705ggbcg) {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
