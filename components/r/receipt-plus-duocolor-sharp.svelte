<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d_vdeimer"/><path class="qq7f_hbum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:receipt-plus-duocolor-sharp" {...props}></Icon>
<style>
:global(.d_vdeimer) {
  stroke-opacity: 0.4;
  d: path("M9 11h6m-3-3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qq7f_hbum) {
  d: path("M12 3h8v18l-4-2l-4 2l-4-2l-4 2V3z");
}

</style>
