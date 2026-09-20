<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="pty_wsbvs"/><path class="k0x593b0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:invoice-issue-outline-regular" {...props}></Icon>
<style>
:global(.csyuhrrop) {
  d: path("M5 14V3h14v11");
}

:global(.k0x593b0b) {
  d: path("M13.5 6.5 16 9l-2.5 2.5");
}

:global(.nreq_9ofo) {
  d: path("M2 11v10h20V11L12 21Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

</style>
