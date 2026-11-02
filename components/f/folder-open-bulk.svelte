<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x14gn1bxi"/><path class="uduocrpst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-open-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.uduocrpst) {
  d: path("m4.051 19.684l2-6c.317-.95.806-1.851 1.518-2.563c.648-.647 1.487-1.119 2.424-1.121H19c.497 0 .959.192 1.322.529c.99.922 1.028 2.583.627 3.787l-1 3c-.317.95-.806 1.851-1.518 2.563C17.785 20.525 16.933 21 16 21H5a1.002 1.002 0 0 1-.949-1.316M10 12c-.387 0-.762.28-1.017.535c-.492.492-.816 1.126-1.034 1.781L6.387 19H16c.157 0 .311-.048.451-.116c.213-.103.4-.253.566-.419c.492-.492.816-1.126 1.034-1.781l1-3c.147-.442.203-.972.054-1.421a.7.7 0 0 0-.139-.263Z");
}

:global(.x14gn1bxi) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.707 3.293L12.414 5H17a3 3 0 0 1 3 3v2.281c.881.55 1.207 1.657 1.19 2.645a4.7 4.7 0 0 1-.241 1.39l-1 3c-.317.95-.806 1.851-1.518 2.563C17.785 20.525 16.933 21 16 21H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h5c.265 0 .52.105.707.293");
}

</style>
