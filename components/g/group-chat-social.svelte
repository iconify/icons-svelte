<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs4t2u6su"/><path class="t1ov0-q9j"/><circle class="l-zqvscmh"/><circle class="um74zsb4n"/><path class="qv6ad4bzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:group-chat-social" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l-zqvscmh) {
  cx: 7.5px;
  cy: 11px;
  r: 1.25px;
}

:global(.qs4t2u6su) {
  d: path("M7.25 4.75a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2V11a2 2 0 0 1-2 2v2.5l-2-2");
}

:global(.qv6ad4bzu) {
  d: path("M5.5 15a2 2 0 0 1 4 0m.5 0a2 2 0 0 1 4 0");
}

:global(.t1ov0-q9j) {
  d: path("M2.75 9.5A2.5 2.5 0 0 1 5.25 7h9a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-5L6.5 20.5a.77.77 0 0 1-1.25-.6V18a2.5 2.5 0 0 1-2.5-2.5Z");
}

:global(.um74zsb4n) {
  cx: 12px;
  cy: 11px;
  r: 1.25px;
}

</style>
