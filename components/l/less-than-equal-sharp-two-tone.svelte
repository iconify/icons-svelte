<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yk5a-tmjg"/><path clip-rule="evenodd" class="kl4zvkbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:less-than-equal-sharp-two-tone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kl4zvkbzg) {
  fill-rule: evenodd;
  d: path("M17 18V20H7V18H17Z");
}

:global(.yk5a-tmjg) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.773 5.7L9.887 10L17 14.45L16.47 15.29L15.94 16.14L7.47 10.85C7.178 10.66 7 10.34 7 10C7 9.66 7.177 9.33 7.47 9.15L15.713 4L16.773 5.7Z");
}

</style>
