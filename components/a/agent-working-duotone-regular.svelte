<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be83lpb1j"/><path class="nrlkc9bnf"/><path class="w28ybhbjm"/><path class="h7bcztycq"/><path class="h0r-78wsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-working-duotone-regular" {...props}></Icon>
<style>
:global(.be83lpb1j) {
  fill: currentColor;
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h0r-78wsa) {
  d: path("M17 10v4");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nrlkc9bnf) {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.w28ybhbjm) {
  d: path("M7 10v4");
}

</style>
