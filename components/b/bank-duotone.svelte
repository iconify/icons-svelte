<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajmr6ilnu"/><path class="r2w_weexo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bank-duotone" {...props}></Icon>
<style>
:global(.ajmr6ilnu) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 7H3l9-4l9 4Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.r2w_weexo) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7H3l9-4l9 4zM3 21h18M6 11v6m4-6v6m4-6v6m4-6v6");
}

</style>
