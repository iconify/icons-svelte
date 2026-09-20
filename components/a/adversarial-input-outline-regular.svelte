<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iymet_cml"/><path class="vc5bmsqzd"/><path class="uhawluh-v"/><path class="w41b5cbwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:adversarial-input-outline-regular" {...props}></Icon>
<style>
:global(.iymet_cml) {
  d: path("M15.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V8l4 -4h3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uhawluh-v) {
  d: path("M6.5 9.5 9 12l-2.5 2.5");
}

:global(.vc5bmsqzd) {
  d: path("M5 12h4");
}

:global(.w41b5cbwu) {
  d: path("M15.5 9.5 13 12h2.5L13 14.5");
}

</style>
