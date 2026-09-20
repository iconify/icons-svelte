<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e6eri9pjq"/><path class="ta4vmeb9o"/><path class="puve50t9i"/><path class="r_b50rbgh"/><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="n_1n94xtx"/><path class="hu1l55dbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compress-context-duotone-thin" {...props}></Icon>
<style>
:global(.b4x_isbqv) {
  d: path("M8 6H5v12h3");
}

:global(.d_6ujebpi) {
  d: path("M16 6h3v12h-3");
}

:global(.e6eri9pjq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6H5v12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.puve50t9i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 8.5 12 11l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r_b50rbgh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 15.5 12 13l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ta4vmeb9o) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 6h3v12h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
