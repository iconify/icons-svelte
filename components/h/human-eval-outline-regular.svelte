<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="myekf3bzc"/><path class="cpvmwnddk"/><path class="zt8wecbdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:human-eval-outline-regular" {...props}></Icon>
<style>
:global(.cpvmwnddk) {
  d: path("M2 19a5 5 0 0 1 10 0");
}

:global(.myekf3bzc) {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zt8wecbdr) {
  d: path("m13 14 3 3 5 -5");
}

</style>
