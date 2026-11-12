<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyjon0btb"/><path class="t1in8db2h"/><path class="ogw7e4m-c"/><path class="fpn8si0az"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-line-duotone" {...props}></Icon>
<style>
:global(.fpn8si0az) {
  d: path("M20 16H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hyjon0btb) {
  d: path("M10 3L5 21");
}

:global(.ogw7e4m-c) {
  d: path("M22 9H4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.t1in8db2h) {
  d: path("M19 3L14 21");
}

</style>
