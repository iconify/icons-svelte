<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="obacg4phc"/><path class="d-63bob2d"/><path class="vddqnrbls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:governance-token" {...props}></Icon>
<style>
:global(.d-63bob2d) {
  d: path("M3.5 9v5.5a8.5 5.5 0 0 0 17 0V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.obacg4phc) {
  d: path("M3.5 9a8.5 5.5 0 1 0 17 0a8.5 5.5 0 1 0-17 0");
}

:global(.vddqnrbls) {
  d: path("m9 9l2 2l4-4");
}

</style>
