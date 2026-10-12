<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmsa3vmcx"/><rect class="s639urbmm"/><path class="m6nkjhiin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cubicle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kmsa3vmcx) {
  d: path("M2.75 21.25v-15a1.5 1.5 0 0 1 1.5-1.5h15.5a1.5 1.5 0 0 1 1.5 1.5v15M2.75 16h18.5");
}

:global(.m6nkjhiin) {
  d: path("M12 13v3");
}

:global(.s639urbmm) {
  width: 7px;
  height: 5px;
  x: 8.5px;
  y: 8px;
  rx: 1px;
}

</style>
