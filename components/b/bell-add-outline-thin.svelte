<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="acx2mjbnt"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bell-add-outline-thin" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.srzgk7jml) {
  d: path("M3 17a9 9 0 0 1 18 0");
}

</style>
