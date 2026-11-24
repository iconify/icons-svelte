<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qixzcgbzi"/><path class="ubzqde8wq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-plus-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.qixzcgbzi) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m6 17l9-9a1.415 1.415 0 0 1 2 0l1 1a1.415 1.415 0 0 1 0 2l-9 9H6Z");
}

:global(.ubzqde8wq) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 20v-3l9-9a1.414 1.414 0 0 1 2 0l1 1a1.414 1.414 0 0 1 0 2l-9 9zm8-11l3 3M4 7h6M7 4v6");
}

</style>
