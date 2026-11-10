<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6sdblw5a"/><path clip-rule="evenodd" class="sbcvy3bxl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:plus-forward-slash-minus-sharp-two-tone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.r6sdblw5a) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.118 2.15L5.521 23L3.883 21.85L18.48 1L20.118 2.15Z");
}

:global(.sbcvy3bxl) {
  fill-rule: evenodd;
  d: path("M6.999 5H11V7H6.999L6.997 11L4.997 11L4.999 7H1V5H4.999L5 1H7L6.999 5ZM23 19H13V17H23V19Z");
}

</style>
