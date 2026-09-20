<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zk_4bjb4m"/><path class="esh17sbch"/><path class="vhf3_kexp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bathroom-sink-outline-thin" {...props}></Icon>
<style>
:global(.esh17sbch) {
  d: path("M7 12V7h3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vhf3_kexp) {
  d: path("M12 16v5");
}

:global(.zk_4bjb4m) {
  d: path("M4 12h16a10 10 0 0 1 -16 0");
}

</style>
