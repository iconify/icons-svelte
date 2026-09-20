<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr18_ccge"/><path class="bod4n0b3z"/><path class="qhxvxhy0o"/><path class="azj37obeu"/><path class="tu0fdo1xi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bedroom-outline-thin" {...props}></Icon>
<style>
:global(.azj37obeu) {
  d: path("M12 2v10");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qhxvxhy0o) {
  d: path("M7 4a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.rr18_ccge) {
  d: path("M2 21v-6h20v6");
}

:global(.tu0fdo1xi) {
  d: path("M7 7h10");
}

</style>
