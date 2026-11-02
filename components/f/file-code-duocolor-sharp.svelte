<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="msqoaibfe"/><path class="cesmxqb_w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-code-duocolor-sharp" {...props}></Icon>
<style>
:global(.cesmxqb_w) {
  d: path("M13 3H5v18h14V9m-6-6l6 6m-6-6v6h6");
}

:global(.msqoaibfe) {
  stroke-opacity: 0.4;
  d: path("m14 13l2 2l-2 2m-4 0l-2-2l2-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
