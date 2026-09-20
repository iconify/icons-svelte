<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="szkijcbqo"/><path class="ifsz0izyq"/><path class="j-rdw_bvv"/><path class="t1rg4fbhf"/><path class="pf-zwj5ei"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:following-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifsz0izyq) {
  d: path("M12 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.j-rdw_bvv) {
  d: path("M11 17a4 4 0 0 1 8 0");
}

:global(.pf-zwj5ei) {
  d: path("m6 10 2 2 -2 2");
}

:global(.szkijcbqo) {
  fill: currentColor;
  d: path("M12 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.t1rg4fbhf) {
  d: path("M3 12h5");
}

</style>
