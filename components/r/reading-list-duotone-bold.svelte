<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zjwn55blz"/><path class="zkld0ib7h"/><path class="hgmedzbsm"/><path class="h2ryw2b8h"/><path class="szeqx6bdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reading-list-duotone-bold" {...props}></Icon>
<style>
:global(.h2ryw2b8h) {
  d: path("M13 13h7");
}

:global(.hgmedzbsm) {
  d: path("M13 9h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.szeqx6bdv) {
  d: path("M13 17h5");
}

:global(.zjwn55blz) {
  fill: currentColor;
  d: path("M4 6h6v10l-3 -3 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zkld0ib7h) {
  d: path("M4 6h6v10l-3 -3 -3 3Z");
}

</style>
