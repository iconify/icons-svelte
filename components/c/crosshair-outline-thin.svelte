<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dx5s6zbrc"/><path class="zkgvk4bog"/><path class="lr02_ebwb"/><path class="glfpqop5h"/><path class="pcm_oppbo"/><path class="n3p0zmbop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crosshair-outline-thin" {...props}></Icon>
<style>
:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.glfpqop5h) {
  d: path("M2 12h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lr02_ebwb) {
  d: path("M12 19v3");
}

:global(.n3p0zmbop) {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pcm_oppbo) {
  d: path("M19 12h3");
}

:global(.zkgvk4bog) {
  d: path("M12 2v3");
}

</style>
