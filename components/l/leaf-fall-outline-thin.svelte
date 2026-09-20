<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vi0rmgvkt"/><path class="d5ewpzb2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leaf-fall-outline-thin" {...props}></Icon>
<style>
:global(.d5ewpzb2a) {
  d: path("M12 20c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vi0rmgvkt) {
  d: path("M4 11c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

</style>
