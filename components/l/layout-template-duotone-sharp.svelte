<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eiqc75bnl"/><path class="w9ra8jb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layout-template-duotone-sharp" {...props}></Icon>
<style>
:global(.eiqc75bnl) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 4v5H4V4Zm-8 9v7H4v-7Zm8 0v7h-4v-7Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.w9ra8jb4q) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 13h8v7H4Zm12 0h4v7h-4ZM4 4h16v5H4Z");
}

</style>
