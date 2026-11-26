<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sc5errbsq"/><path class="g9r55mb4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-align-right-duotone" {...props}></Icon>
<style>
:global(.g9r55mb4m) {
  d: path("M3 3H21M3 21H21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sc5errbsq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 6L19 6C20.6569 6 22 7.3431 22 9L22 15C22 16.6569 20.6569 18 19 18L13 18C11.3431 18 10 16.6569 10 15L10 9C10 7.3431 11.3431 6 13 6Z");
  stroke: none;
}

</style>
