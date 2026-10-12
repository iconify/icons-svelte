<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it3lw8bdz"/><rect class="qa-awj9mj"/><path class="o8m0oo8cr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pile-driver" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it3lw8bdz) {
  d: path("M10.5 8V2.75h3V8");
}

:global(.o8m0oo8cr) {
  d: path("M12 12v9.25M2.75 19.5H9m6 0h6.25m-12.75-3L6.75 15m8.75 1.5l1.75-1.5");
}

:global(.qa-awj9mj) {
  width: 6.5px;
  height: 4px;
  x: 8.75px;
  y: 8px;
  rx: 1px;
}

</style>
