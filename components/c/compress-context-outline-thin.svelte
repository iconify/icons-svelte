<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="n_1n94xtx"/><path class="hu1l55dbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compress-context-outline-thin" {...props}></Icon>
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

:global(.hu1l55dbx) {
  d: path("M9.5 15.5 12 13l2.5 2.5");
}

:global(.n_1n94xtx) {
  d: path("M9.5 8.5 12 11l2.5 -2.5");
}

</style>
