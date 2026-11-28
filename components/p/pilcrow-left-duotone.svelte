<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zajw4fbmx"/><path class="z3w0q-bsi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:pilcrow-left-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.z3w0q-bsi) {
  d: path("M21 17H3M7 13L3 17L7 21");
}

:global(.zajw4fbmx) {
  stroke-opacity: 0.4;
  d: path("M21 3H13C11.3431 3 10 4.3431 10 6C10 7.6569 11.3431 9 13 9H15M15 3V13M20 3V13");
}

</style>
