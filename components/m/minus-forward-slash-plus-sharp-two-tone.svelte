<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r6sdblw5a"/><path clip-rule="evenodd" class="k191mlbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:minus-forward-slash-plus-sharp-two-tone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k191mlbcl) {
  fill-rule: evenodd;
  d: path("M18.999 17H23V19H18.999L18.997 23L16.997 23L16.999 19H13V17H16.999L17 13H19L18.999 17ZM11 7H1V5H11V7Z");
}

:global(.r6sdblw5a) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.118 2.15L5.521 23L3.883 21.85L18.48 1L20.118 2.15Z");
}

</style>
