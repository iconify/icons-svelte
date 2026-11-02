<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lln0f3f1b"/><path class="c45dbccyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-check-duotone-sharp" {...props}></Icon>
<style>
:global(.c45dbccyh) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 3h14v14H7ZM3 9v12h12m-4-11l2 2l4-4");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.lln0f3f1b) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 3h14v14H7Z");
}

</style>
