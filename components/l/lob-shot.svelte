<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bvbl-ubne"/><path class="kr8kv1sav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lob-shot" {...props}></Icon>
<style>
:global(.bvbl-ubne) {
  d: path("M2.5 20h19M12 20v-8m-8.5 4.5Q11-4 17.25 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kr8kv1sav) {
  d: path("M15.75 12.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
