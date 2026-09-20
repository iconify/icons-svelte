<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6an06b6t"/><path class="znztjab3f"/><path class="h03wmtogt"/><path class="czikht1og"/><path class="sbzfdkqzv"/><path class="jauaj8j3z"/><path class="tt7ypiikb"/><path class="n-059ea3n"/><path class="du3agkbjb"/><path class="f8c172gmh"/><path class="zrdou8b0n"/><path class="kl9vv3e1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:multiple-choice-duotone-thin" {...props}></Icon>
<style>
:global(.czikht1og) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 6h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f8c172gmh) {
  d: path("M12 6h9");
}

:global(.h03wmtogt) {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.jauaj8j3z) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 18h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kl9vv3e1t) {
  d: path("M12 18h6");
}

:global(.n-059ea3n) {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.p6an06b6t) {
  fill: currentColor;
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sbzfdkqzv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tt7ypiikb) {
  d: path("M5 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.znztjab3f) {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>
