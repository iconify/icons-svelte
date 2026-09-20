<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cu26jmb_i"/><path class="x50q_4bdr"/><path class="c4axibc2h"/><path class="yk993owos"/><path class="qot4e3zhe"/><path class="dn4882bil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:effective-date-outline-thin" {...props}></Icon>
<style>
:global(.c4axibc2h) {
  d: path("M8 3v4");
}

:global(.cu26jmb_i) {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.dn4882bil) {
  d: path("M12 15h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qot4e3zhe) {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.yk993owos) {
  d: path("M16 3v4");
}

</style>
