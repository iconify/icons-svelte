<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="abnm6smsv"/><path class="ymqlmabed"/><path class="gcalxb98a"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:citation-span-outline-regular" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.gjmq94baq) {
  d: path("M15 11v4");
}

:global(.l3hfq7bhw) {
  d: path("M9 11v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ymqlmabed) {
  d: path("M8 8h7");
}

</style>
