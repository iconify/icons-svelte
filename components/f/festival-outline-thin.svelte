<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d9j2xyvdd"/><path class="yvwbi-etd"/><path class="vm7z8yblu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:festival-outline-thin" {...props}></Icon>
<style>
:global(.d9j2xyvdd) {
  d: path("m3 19 9 -9 9 9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vm7z8yblu) {
  d: path("m12 3 4 4h-4");
}

:global(.yvwbi-etd) {
  d: path("M12 2v8");
}

</style>
