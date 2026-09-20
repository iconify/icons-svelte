<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="caznxbcdb"/><path class="ag27qibsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-up-down-outline-thin" {...props}></Icon>
<style>
:global(.ag27qibsz) {
  d: path("m7 15 5 5 5 -5");
}

:global(.caznxbcdb) {
  d: path("m7 9 5 -5 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
