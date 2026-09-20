<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cvoep2bmy"/><path class="nc6yfes3p"/><path class="zrwkhybyf"/><path class="d8abqfbpc"/><path class="tu0fdo1xi"/><path class="ptznkxbtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:electric-meter-duotone-bold" {...props}></Icon>
<style>
:global(.cvoep2bmy) {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.nc6yfes3p) {
  fill: currentColor;
  d: path("M9 14h6l-3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ptznkxbtu) {
  d: path("M9 14h6l-3 3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tu0fdo1xi) {
  d: path("M7 7h10");
}

:global(.zrwkhybyf) {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
