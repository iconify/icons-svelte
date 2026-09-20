<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crydxpbzr"/><path class="vf5uqoncb"/><path class="utcr20lug"/><path class="n8sqmebht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bird-bath-duotone-thin" {...props}></Icon>
<style>
:global(.crydxpbzr) {
  fill: currentColor;
  d: path("M4 7h16c0 4 -4 6 -8 6s-8 -2 -8 -6");
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

:global(.n8sqmebht) {
  d: path("M7 18h10");
}

:global(.utcr20lug) {
  d: path("M12 13v5");
}

:global(.vf5uqoncb) {
  d: path("M4 7h16c0 4 -4 6 -8 6s-8 -2 -8 -6");
}

</style>
