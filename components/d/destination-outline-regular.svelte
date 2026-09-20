<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qad3kqbgr"/><path class="sfjortb-o"/><path class="ucuiysazu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:destination-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qad3kqbgr) {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

:global(.sfjortb-o) {
  d: path("M12 7v5");
}

:global(.ucuiysazu) {
  d: path("M9.5 9.5 12 12l2.5 -2.5");
}

</style>
