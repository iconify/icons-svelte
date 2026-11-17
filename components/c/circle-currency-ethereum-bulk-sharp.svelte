<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="fbl85mbxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-currency-ethereum-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fbl85mbxf) {
  d: path("M16.832 11.445a1 1 0 0 1 0 1.11l-4 6a1 1 0 0 1-1.664 0l-4-6a1 1 0 0 1 0-1.11l4-6a1 1 0 0 1 1.664 0Zm-2.451-.071L12 7.803l-2.381 3.571l2.381.595Zm-.648 2.223l-1.49.373a1 1 0 0 1-.486 0l-1.49-.373l1.733 2.6Z");
}

:global(.riis51qtn) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

</style>
