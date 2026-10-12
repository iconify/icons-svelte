<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q1mw3qbwr"/><path class="o74-2lb8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:djembe" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o74-2lb8l) {
  d: path("m8 7l2 3l2-3l2 3l2-3");
}

:global(.q1mw3qbwr) {
  d: path("M4.25 4h15.5c0 4-2.5 7.25-5.25 9.25l2.5 8H7l2.5-8C6.75 11.25 4.25 8 4.25 4");
}

</style>
