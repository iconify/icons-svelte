<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rxwr8htky"/><path class="j4xts30pb"/><path class="jcwhwvnse"/><path class="l3ca9u8kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:consumer-duotone-regular" {...props}></Icon>
<style>
:global(.j4xts30pb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.24 16.24a6 6 0 1 1 0 -8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jcwhwvnse) {
  d: path("M12.24 16.24a6 6 0 1 1 0 -8.5");
}

:global(.l3ca9u8kt) {
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rxwr8htky) {
  fill: currentColor;
  d: path("M17 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
