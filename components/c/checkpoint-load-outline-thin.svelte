<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="hpd-e505b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-load-outline-thin" {...props}></Icon>
<style>
:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hpd-e505b) {
  d: path("M16.5 15.5 19 13l2.5 2.5");
}

:global(.ni-_lk7vs) {
  d: path("M5 5h10v6H5");
}

:global(.ojq3d2bwe) {
  d: path("M5 3v18");
}

</style>
