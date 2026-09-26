<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g-uqi08aq"/><path class="b5by-czkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-right-duotone" {...props}></Icon>
<style>
:global(.b5by-czkh) {
  d: path("M13 17L18 12L13 7");
}

:global(.g-uqi08aq) {
  stroke-opacity: 0.4;
  d: path("M6 17L11 12L6 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
