<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="koat62btr"/><path class="zk-pn1cfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:farm-cat" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.koat62btr) {
  d: path("M12.104 21H3V10l9-7l9 7v1.696");
}

:global(.zk-pn1cfh) {
  d: path("M7.5 14H10a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 10 21H7.5A1.5 1.5 0 0 1 6 19.5v-4A1.5 1.5 0 0 1 7.5 14M6 14l5.5 7m0-7L6 21m8.5-6.5l2 2h3l2-2V19c0 1.75-1.5 2.75-3.5 2.75s-3.5-1-3.5-2.75Z");
}

</style>
