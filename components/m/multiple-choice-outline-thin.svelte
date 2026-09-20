<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tt7ypiikb"/><path class="n-059ea3n"/><path class="du3agkbjb"/><path class="f8c172gmh"/><path class="zrdou8b0n"/><path class="kl9vv3e1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multiple-choice-outline-thin" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f8c172gmh) {
  d: path("M12 6h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kl9vv3e1t) {
  d: path("M12 18h6");
}

:global(.n-059ea3n) {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tt7ypiikb) {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>
