<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mmx7g9jzy"/><path class="it88l1wbh"/><path class="w_jkatblo"/><path class="qg37n0byb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:film-roll-outline-regular" {...props}></Icon>
<style>
:global(.it88l1wbh) {
  d: path("M7 7v10");
}

:global(.mmx7g9jzy) {
  d: path("M3 7v10h18V7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qg37n0byb) {
  d: path("M17 7v10");
}

:global(.w_jkatblo) {
  d: path("M12 7v10");
}

</style>
