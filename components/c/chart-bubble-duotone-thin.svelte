<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djxmm5iax"/><path class="s69msxbdh"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="aymrypeyx"/><path class="bdfic-buk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-bubble-duotone-thin" {...props}></Icon>
<style>
:global(.aymrypeyx) {
  d: path("M7 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bdfic-buk) {
  d: path("M12 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.djxmm5iax) {
  fill: currentColor;
  d: path("M7 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.s69msxbdh) {
  fill: currentColor;
  d: path("M12 10a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
