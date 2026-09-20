<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nrlkc9bnf"/><path class="e2c9xqbhi"/><path class="lerbluboq"/><path class="ylnvyeb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:credit-hours-outline-regular" {...props}></Icon>
<style>
:global(.e2c9xqbhi) {
  d: path("M12 7v5h4");
}

:global(.lerbluboq) {
  d: path("M17 4h4");
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

:global(.ylnvyeb_w) {
  d: path("M19 2v4");
}

</style>
