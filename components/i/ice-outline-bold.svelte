<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="plts5tbsc"/><path class="e70mzkkad"/><path class="ricsl-blc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:ice-outline-bold" {...props}></Icon>
<style>
:global(.e70mzkkad) {
  d: path("m6 9 3 3h6l3 -3");
}

:global(.plts5tbsc) {
  d: path("M6 4h12v11l-6 6 -6 -6Z");
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
