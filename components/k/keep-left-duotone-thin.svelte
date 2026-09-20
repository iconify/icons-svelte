<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ptz0jvb3k"/><path class="gsz4k90ej"/><path class="s5-57zhtp"/><path class="h-ljjxb1p"/><path class="izmrq5b4m"/><path class="eeoxujb4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-left-duotone-thin" {...props}></Icon>
<style>
:global(.eeoxujb4a) {
  d: path("m14 11 5 -5");
}

:global(.gsz4k90ej) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 10.5V6h4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h-ljjxb1p) {
  d: path("M12 22v-9L5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izmrq5b4m) {
  d: path("M5 10.5V6h4.5");
}

:global(.ptz0jvb3k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 22v-9L5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s5-57zhtp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 11 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
