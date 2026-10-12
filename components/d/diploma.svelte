<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cxje5zb4p"/><path class="b60px0bcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diploma" {...props}></Icon>
<style>
:global(.b60px0bcu) {
  d: path("M7.25 6.5V5.25a2 2 0 0 0-2-2M16.75 15v1.25a2 2 0 0 0 2 2m-8.5-9.75h3.5m-3.5 3h3.5m-3.25 6.75v3L12 20l1.5 1.25v-3");
}

:global(.cxje5zb4p) {
  d: path("M5.25 3.25h9.5a2 2 0 0 1 2 2V15h4v1.25a2 2 0 0 1-2 2h-9.5a2 2 0 0 1-2-2V6.5h-4V5.25a2 2 0 0 1 2-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
