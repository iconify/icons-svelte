<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q2-zfvbmg"/><path class="u_8fqnblg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-fresh-produce" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q2-zfvbmg) {
  d: path("M12 8S7 5.5 5 9.5c-1.5 3.5 1 10 7 10s8.5-6.5 7-10c-2-4-7-1.5-7-1.5");
}

:global(.u_8fqnblg) {
  d: path("M12 8c0-2.5 1.5-4.5 4-5");
}

</style>
