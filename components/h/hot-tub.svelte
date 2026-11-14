<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v1nyzjbqq"/><path class="pso4sy5ql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hot-tub" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pso4sy5ql) {
  d: path("M3 11v8a9 2.5 0 0 0 18 0v-8M7.5 12.75v8.5M12 13v8.5m4.5-8.75v8.5M8 7.5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5m4 5c-.75-.75-.75-1.75 0-2.5s.75-1.75 0-2.5");
}

:global(.v1nyzjbqq) {
  d: path("M3 11a9 2 0 1 0 18 0a9 2 0 1 0-18 0");
}

</style>
