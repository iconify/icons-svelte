<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uyem4glxm"/><path class="zhybnub4h"/><path class="t0-mwc0xy"/><path class="o793-7bra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:freight-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o793-7bra) {
  d: path("M17 10v6");
}

:global(.t0-mwc0xy) {
  d: path("M12 10v6");
}

:global(.uyem4glxm) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.zhybnub4h) {
  d: path("M7 10v6");
}

</style>
