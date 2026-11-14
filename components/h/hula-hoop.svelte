<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e179vlb3j"/><path class="ltkj5n90t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hula-hoop" {...props}></Icon>
<style>
:global(.e179vlb3j) {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 3.5v7M9 21l3-6.5l3 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ltkj5n90t) {
  d: path("m8 6l4 3l4-3M3.5 13a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0");
}

</style>
