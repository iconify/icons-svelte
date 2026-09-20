<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="esolkqbpc"/><path class="xvrtzwm1e"/><path class="s6yzsme1j"/><path class="c-pcdbceg"/><path class="yar83jxfe"/><path class="oqw_13bxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:light-rain-duotone-bold" {...props}></Icon>
<style>
:global(.c-pcdbceg) {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

:global(.esolkqbpc) {
  fill: currentColor;
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.oqw_13bxd) {
  d: path("m15 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s6yzsme1j) {
  fill: currentColor;
  d: path("m15 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xvrtzwm1e) {
  fill: currentColor;
  d: path("m9 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yar83jxfe) {
  d: path("m9 17 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
