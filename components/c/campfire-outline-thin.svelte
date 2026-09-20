<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ivk9cqevc"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:campfire-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ivk9cqevc) {
  d: path("M12 17c-4 -2 -5.5 -6 -3 -10 1.5 2.5 3 2.5 3 1 0 -2.5 -1.5 -4 0 -6 3 2.5 5.5 5 5.5 9 0 3.5 -2.5 5 -5.5 6");
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

</style>
