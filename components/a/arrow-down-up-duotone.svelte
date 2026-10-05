<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hahcwdkdq"/><path class="l8pqsacur"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-up-duotone" {...props}></Icon>
<style>
:global(.hahcwdkdq) {
  stroke-opacity: 0.4;
  d: path("M18 21L18 3M15 6L18 3L21 6");
}

:global(.l8pqsacur) {
  d: path("M6 3L6 21M3 18L6 21L9 18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
