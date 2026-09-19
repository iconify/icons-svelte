<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z87easbaf"/><path class="a-9iumbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:norisbank" {...props}></Icon>
<style>
:global(.a-9iumbia) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.063 4.499c-5.88 3.609-10.549 13.744-7.815 28.632");
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z87easbaf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.15 2.58C17.93 4.448 8.257 13.448 6.407 20.387M26.514 2.646c-4.774 2.45-13.505 12.4-13.827 21.99M30.168 3.399c-5.327 3.028-12.406 13.246-11.2 25.484");
}

</style>
