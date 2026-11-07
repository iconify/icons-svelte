<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j-wf5hp6d"/><path class="g-wjh3b_n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-double-duotone" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g-wjh3b_n) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0V6c0-.919 1.081-1.46 2-1l4 2m-6 2l4 2");
}

:global(.j-wf5hp6d) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 17a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
