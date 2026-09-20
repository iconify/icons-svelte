<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hmx2r2iko"/><path class="teamv5bhf"/><path class="fjiurnzxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cookie-outline-regular" {...props}></Icon>
<style>
:global(.fjiurnzxd) {
  d: path("M12 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hmx2r2iko) {
  d: path("M12 4a8 8 0 1 0 8 8 3 3 0 0 1 -4 -4 3 3 0 0 1 -4 -4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.teamv5bhf) {
  d: path("M8 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
