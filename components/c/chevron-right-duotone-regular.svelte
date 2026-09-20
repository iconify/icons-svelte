<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s6bcnpbqe"/><path class="mcepj1byz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevron-right-duotone-regular" {...props}></Icon>
<style>
:global(.mcepj1byz) {
  d: path("m9 5 7 7 -7 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s6bcnpbqe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
