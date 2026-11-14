<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfop0pw6r"/><path class="s_tfcz39x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carpet-persian" {...props}></Icon>
<style>
:global(.gfop0pw6r) {
  d: path("M4.5 4.5h15a2 2 0 0 1 2 2v10l-3 3h-14a2 2 0 0 1-2-2v-11a2 2 0 0 1 2-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_tfcz39x) {
  d: path("M21.5 16.5q-2.75-.25-3 3M13.061 8.561l2.378 2.378a1.5 1.5 0 0 1 0 2.122l-2.378 2.378a1.5 1.5 0 0 1-2.122 0l-2.378-2.378a1.5 1.5 0 0 1 0-2.122l2.378-2.378a1.5 1.5 0 0 1 2.122 0M12 12h.01");
}

</style>
