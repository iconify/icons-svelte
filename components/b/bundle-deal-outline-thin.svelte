<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pywr_yykw"/><path class="m0hvambgh"/><path class="l517yxbln"/><path class="x1_r36phd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bundle-deal-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.m0hvambgh) {
  d: path("M16 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.pywr_yykw) {
  d: path("m4 12 8 -8h8v8l-8 8Z");
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

</style>
