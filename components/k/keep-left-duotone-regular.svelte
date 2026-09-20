<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cncme659a"/><path class="vi1za7buk"/><path class="kp7w92boc"/><path class="h-ljjxb1p"/><path class="izmrq5b4m"/><path class="eeoxujb4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-left-duotone-regular" {...props}></Icon>
<style>
:global(.cncme659a) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 22v-9L5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eeoxujb4a) {
  d: path("m14 11 5 -5");
}

:global(.h-ljjxb1p) {
  d: path("M12 22v-9L5 6");
}

:global(.izmrq5b4m) {
  d: path("M5 10.5V6h4.5");
}

:global(.kp7w92boc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 11 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vi1za7buk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 10.5V6h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
