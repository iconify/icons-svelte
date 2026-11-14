<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su8lvkbdm"/><path class="ta_u09b7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chat-attachment" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.su8lvkbdm) {
  d: path("M5 2.75h14a2 2 0 0 1 2 2V15.5a2 2 0 0 1-2 2h-8L7 21v-3.5H5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2");
}

:global(.ta_u09b7t) {
  d: path("M12 9v4a1.5 1.5 0 0 0 3 0V8.5a3 3 0 0 0-6 0v6");
}

</style>
