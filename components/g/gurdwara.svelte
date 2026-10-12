<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ab3j5tynr"/><path class="rj62d1szg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gurdwara" {...props}></Icon>
<style>
:global(.ab3j5tynr) {
  width: 17.5px;
  height: 7.75px;
  x: 3.25px;
  y: 13.5px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rj62d1szg) {
  d: path("M7.75 13.5c0-3 2-4.75 4.25-6.75c2.25 2 4.25 3.75 4.25 6.75Zm-4.5 0c0-1.5.75-2.5 1.75-3c1 .5 1.75 1.5 1.75 3Zm14 0c0-1.5.75-2.5 1.75-3c1 .5 1.75 1.5 1.75 3ZM12 6.75V3m-1.5 18.25v-2.5a1.5 1.5 0 0 1 3 0v2.5");
}

</style>
