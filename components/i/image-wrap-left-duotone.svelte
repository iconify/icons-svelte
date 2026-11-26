<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-cgzablu"/><path class="shy9kldmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-wrap-left-duotone" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p-cgzablu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6L11 6C12.6569 6 14 7.3431 14 9L14 15C14 16.6569 12.6569 18 11 18L5 18C3.3431 18 2 16.6569 2 15L2 9C2 7.3431 3.3431 6 5 6Z");
  stroke: none;
}

:global(.shy9kldmf) {
  d: path("M3 3H21M3 21H21M17 9H21M17 15H21");
}

</style>
