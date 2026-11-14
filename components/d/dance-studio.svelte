<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgqtned1z"/><path class="tmebgacce"/><path class="rcio_lb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dance-studio" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rcio_lb6f) {
  d: path("m8.5 11l3.5 1.75l3.5-2.25M12 12.75v2.75l-2.75 2.75M12 15.5l2.75 2.75");
}

:global(.tmebgacce) {
  fill: currentColor;
  d: path("M12.5 9.5h.01");
}

:global(.xgqtned1z) {
  d: path("m3.676 9.475l7.25-5.639a1.75 1.75 0 0 1 2.148 0l7.25 5.639A1.75 1.75 0 0 1 21 10.856v8.394A1.75 1.75 0 0 1 19.25 21H4.75A1.75 1.75 0 0 1 3 19.25v-8.394a1.75 1.75 0 0 1 .676-1.381");
}

</style>
