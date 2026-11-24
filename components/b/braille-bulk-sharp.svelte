<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mdestjboj"/><path class="inx-4rbcm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:braille-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.inx-4rbcm) {
  d: path("M6.158 3.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m8 8a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m-8 8a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

:global(.mdestjboj) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.01 3a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-8 8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm8 8a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Z");
}

</style>
