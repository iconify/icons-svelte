<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="igttm1bob"/><path class="s4h39dinw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:list-dashes-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.igttm1bob) {
  d: path("M216 64v128H96V64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s4h39dinw) {
  d: path("M88 64a8 8 0 0 1 8-8h120a8 8 0 0 1 0 16H96a8 8 0 0 1-8-8m128 56H96a8 8 0 1 0 0 16h120a8 8 0 0 0 0-16m0 64H96a8 8 0 1 0 0 16h120a8 8 0 0 0 0-16M56 56H40a8 8 0 0 0 0 16h16a8 8 0 0 0 0-16m0 64H40a8 8 0 1 0 0 16h16a8 8 0 0 0 0-16m0 64H40a8 8 0 1 0 0 16h16a8 8 0 0 0 0-16");
}

</style>
