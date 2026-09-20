<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o8od38cnm"/><path class="tktvzqb2t"/><path class="f__nic5ty"/><path class="mcne0zbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lawn-outline-regular" {...props}></Icon>
<style>
:global(.f__nic5ty) {
  d: path("M12 18V6");
}

:global(.mcne0zbsf) {
  d: path("M17 18c0 -4 1 -7 2 -11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8od38cnm) {
  d: path("M4 18h16");
}

:global(.tktvzqb2t) {
  d: path("M7 18c0 -4 -1 -7 -2 -11");
}

</style>
