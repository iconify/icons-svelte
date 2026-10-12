<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="s1dqcacah"/><circle class="ons53cb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hubcap" {...props}></Icon>
<style>
:global(.dbgvcxwad) {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ons53cb4g) {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

:global(.s1dqcacah) {
  d: path("M16.75 12h2m-3.39 3.36l1.41 1.41M12 16.75v2m-3.36-3.39l-1.41 1.41M7.25 12h-2m3.39-3.36L7.23 7.23m4.77.02v-2m3.36 3.39l1.41-1.41");
}

</style>
