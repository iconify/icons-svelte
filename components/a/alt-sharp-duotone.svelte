<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qm0zfug2w"/><path class="xl-o0accs"/><path class="qzvsstb9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:alt-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qm0zfug2w) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 2V4H16.651L8.914 21.406C8.753 21.767 8.395 22 8 22H2V20H7.349L15.142 2.467C15.329 2.242 15.698 2 16 2H22Z");
}

:global(.qzvsstb9d) {
  d: path("M22 20V22H12V20H22Z");
}

:global(.xl-o0accs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 20V22H12V20H22Z");
}

</style>
