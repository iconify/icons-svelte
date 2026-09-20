<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ov4uzldgj"/><path class="smqo3gbuq"/><path class="edg0x3nuq"/><path class="wvha8hh3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:close-duotone-regular" {...props}></Icon>
<style>
:global(.edg0x3nuq) {
  d: path("m5 5 14 14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ov4uzldgj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 5 14 14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.smqo3gbuq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 5 5 19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wvha8hh3o) {
  d: path("M19 5 5 19");
}

</style>
