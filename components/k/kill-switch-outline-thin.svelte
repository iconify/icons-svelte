<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="unjh48car"/><path class="ik93a37tn"/><path class="b3h_rz89d"/><path class="hqwsf4bjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kill-switch-outline-thin" {...props}></Icon>
<style>
:global(.b3h_rz89d) {
  d: path("m6 11 2 2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hqwsf4bjq) {
  d: path("m8 11 -2 2");
}

:global(.ik93a37tn) {
  d: path("M4 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.unjh48car) {
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
}

</style>
