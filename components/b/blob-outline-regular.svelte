<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="el753yuux"/><path class="fb4zxqney"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:blob-outline-regular" {...props}></Icon>
<style>
:global(.el753yuux) {
  d: path("M4 10a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.fb4zxqney) {
  d: path("M12 15a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
