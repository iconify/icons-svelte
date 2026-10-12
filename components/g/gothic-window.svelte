<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zuw80qb6p"/><circle class="o5vk1es1c"/><path class="sifubtbdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gothic-window" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o5vk1es1c) {
  cx: 12px;
  cy: 7.5px;
  r: 1.25px;
}

:global(.sifubtbdm) {
  d: path("M8 21.25V16q0-2.5 2-3.75q2 1.25 2 3.75q0-2.5 2-3.75q2 1.25 2 3.75v5.25M12 16v5.25");
}

:global(.zuw80qb6p) {
  d: path("M5.5 21.25V11.5C5.5 7 8.5 4 12 2.75C15.5 4 18.5 7 18.5 11.5v9.75Z");
}

</style>
