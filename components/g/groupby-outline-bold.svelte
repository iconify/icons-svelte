<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r4nj1cczx"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groupby-outline-bold" {...props}></Icon>
<style>
:global(.eu9kkgbdm) {
  d: path("M9 12h12");
}

:global(.r4nj1cczx) {
  d: path("M6 4H3v16h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxy07wbdf) {
  d: path("M9 7h12");
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

</style>
