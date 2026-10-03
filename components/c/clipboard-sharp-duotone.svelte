<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b0qda_n9u"/><path clip-rule="evenodd" class="eijh9ib1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clipboard-sharp-duotone" {...props}></Icon>
<style>
:global(.b0qda_n9u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C20.5523 3 21 3.4477 21 4L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 4C3 3.4477 3.4477 3 4 3Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.eijh9ib1q) {
  fill-rule: evenodd;
  d: path("M7 1L17 1C17.5523 1 18 1.4477 18 2L18 7C18 7.5523 17.5523 8 17 8L7 8C6.4477 8 6 7.5523 6 7L6 2C6 1.4477 6.4477 1 7 1ZM8 3L8 6L16 6L16 3L8 3Z");
}

</style>
