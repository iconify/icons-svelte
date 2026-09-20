<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="pma7fkjmg"/><path class="r-3ib9fxz"/><path class="nu6kj0bjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:demographic-parity-outline-bold" {...props}></Icon>
<style>
:global(.nu6kj0bjf) {
  d: path("M16 11v7");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pma7fkjmg) {
  d: path("M8 11v7");
}

:global(.r-3ib9fxz) {
  d: path("M12 11v7");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
