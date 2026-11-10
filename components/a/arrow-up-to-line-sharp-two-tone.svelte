<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="opza-6psu"/><path clip-rule="evenodd" class="uhgkbgpkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-to-line-sharp-two-tone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.opza-6psu) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.999 4.754C12.267 4.754 12.524 4.862 12.712 5.054L20.006 12.476L18.58 13.877L12.999 8.197V23H10.999V8.197L5.418 13.877L3.992 12.476L11.326 5.013C11.505 4.864 11.764 4.754 11.999 4.754Z");
}

:global(.uhgkbgpkt) {
  fill-rule: evenodd;
  d: path("M20 1V3H4V1H20Z");
}

</style>
