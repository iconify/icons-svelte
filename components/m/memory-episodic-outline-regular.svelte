<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="be1u5t58a"/><path class="h50arts9k"/><path class="ojg4edcfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-episodic-outline-regular" {...props}></Icon>
<style>
:global(.be1u5t58a) {
  d: path("M6 8h14");
}

:global(.h50arts9k) {
  d: path("M6 12h10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ojg4edcfp) {
  d: path("M6 16h14");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

</style>
