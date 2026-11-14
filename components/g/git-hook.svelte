<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dztisbbjg"/><path class="umncu1g5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:git-hook" {...props}></Icon>
<style>
:global(.dztisbbjg) {
  d: path("M14.5 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umncu1g5k) {
  d: path("M16.5 6.25V14a5.5 5.5 0 0 1-11 0v-4m0 0l3 3");
}

</style>
