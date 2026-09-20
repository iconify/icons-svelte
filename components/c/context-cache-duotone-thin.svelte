<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ut71qqbez"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="ocmla0jdf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-cache-duotone-thin" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ocmla0jdf) {
  d: path("M9 9h6v6H9Z");
}

:global(.ut71qqbez) {
  fill: currentColor;
  d: path("M9 9h6v6H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
