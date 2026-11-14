<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kydwygjxr"/><path class="cjpe75waa"/><path class="bgt_0ob4b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fireplace" {...props}></Icon>
<style>
:global(.bgt_0ob4b) {
  d: path("M12 18.5c-2 0-2.5-1.5-1.75-3c.75-1 1.25-1.5 1.25-3c1.5 1 1 2.25 2 2.75c1 1.25.5 3.25-1.5 3.25");
}

:global(.cjpe75waa) {
  d: path("M9 9h6a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 19v-8.5A1.5 1.5 0 0 1 9 9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kydwygjxr) {
  d: path("M6.125 4h11.75A2.625 2.625 0 0 1 20.5 6.625v11.25a2.625 2.625 0 0 1-2.625 2.625H6.125A2.625 2.625 0 0 1 3.5 17.875V6.625A2.625 2.625 0 0 1 6.125 4");
}

</style>
