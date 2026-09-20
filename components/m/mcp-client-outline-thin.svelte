<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ds5xy8ngy"/><path class="pi15tzbod"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-client-outline-thin" {...props}></Icon>
<style>
:global(.ds5xy8ngy) {
  d: path("M2 10a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.pi15tzbod) {
  d: path("M12 12h8");
}

</style>
