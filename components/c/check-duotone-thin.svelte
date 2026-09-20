<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dwxnb3b1l"/><path class="mwvgb4bmz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:check-duotone-thin" {...props}></Icon>
<style>
:global(.dwxnb3b1l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 12 5.5 5.5L20 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mwvgb4bmz) {
  d: path("m4 12 5.5 5.5L20 7");
}

</style>
