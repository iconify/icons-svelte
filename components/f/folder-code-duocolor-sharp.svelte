<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="puh6zibgx"/><path class="og2hi81sh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-code-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.og2hi81sh) {
  d: path("M12 6h9v14H3V4h7z");
}

:global(.puh6zibgx) {
  stroke-opacity: 0.4;
  d: path("m14 11l2 2l-2 2m-4 0l-2-2l2-2");
}

</style>
