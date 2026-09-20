<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t69363l7x"/><path class="v5slp2tuk"/><path class="vw-y0febs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:reusable-bag-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t69363l7x) {
  d: path("M6 8v13h12V8Z");
}

:global(.v5slp2tuk) {
  d: path("M6 8a3 3 0 0 1 6 0");
}

:global(.vw-y0febs) {
  d: path("M12 8a3 3 0 0 1 6 0");
}

</style>
