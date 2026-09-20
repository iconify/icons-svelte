<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kdq33ubui"/><path class="ux97gqb3r"/><path class="n6ndjw6jf"/><path class="v8c0ocbfs"/><path class="c27cgq4un"/><path class="jlfl_ccwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chunk-add-duotone-bold" {...props}></Icon>
<style>
:global(.c27cgq4un) {
  d: path("M18 8v8");
}

:global(.jlfl_ccwj) {
  d: path("M14 12h8");
}

:global(.kdq33ubui) {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n6ndjw6jf) {
  d: path("M4 9h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ux97gqb3r) {
  d: path("M2 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.v8c0ocbfs) {
  d: path("M4 14h7");
}

</style>
