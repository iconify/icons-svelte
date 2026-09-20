<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gd3gqxb-h"/><path class="xat4txb_y"/><path class="bswpu5b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-invite-outline-regular" {...props}></Icon>
<style>
:global(.bswpu5b0n) {
  d: path("M8 11V4h8v7");
}

:global(.gd3gqxb-h) {
  d: path("M6 11v9h12v-9Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xat4txb_y) {
  d: path("m6 11 6 6 6 -6");
}

</style>
