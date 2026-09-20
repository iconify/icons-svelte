<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsue96bcd"/><path class="q5jw2tb7h"/><path class="aut8y9hmn"/><path class="gwt34irsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:garden-chair-outline-regular" {...props}></Icon>
<style>
:global(.aut8y9hmn) {
  d: path("M7 12v7");
}

:global(.gwt34irsi) {
  d: path("M15 12v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q5jw2tb7h) {
  d: path("m17 12 4 -4");
}

:global(.rsue96bcd) {
  d: path("M5 12h12");
}

</style>
