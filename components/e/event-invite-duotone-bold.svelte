<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e8698-bge"/><path class="gd3gqxb-h"/><path class="xat4txb_y"/><path class="bswpu5b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-invite-duotone-bold" {...props}></Icon>
<style>
:global(.bswpu5b0n) {
  d: path("M8 11V4h8v7");
}

:global(.e8698-bge) {
  fill: currentColor;
  d: path("M6 11v9h12v-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gd3gqxb-h) {
  d: path("M6 11v9h12v-9Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xat4txb_y) {
  d: path("m6 11 6 6 6 -6");
}

</style>
