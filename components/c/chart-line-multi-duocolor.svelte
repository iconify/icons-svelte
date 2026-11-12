<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e7ree_m_g"/><path class="o9cjq4dox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-line-multi-duocolor" {...props}></Icon>
<style>
:global(.e7ree_m_g) {
  stroke-opacity: 0.4;
  d: path("m7 16l4-3l4 2l6-5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o9cjq4dox) {
  d: path("m7 10l4-4l4 3l6-6M3 4v14a2 2 0 0 0 2 2h16");
}

</style>
