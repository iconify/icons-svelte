<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="kzbvcpbzi"/><path class="a-_t87bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:gpslogger" {...props}></Icon>
<style>
:global(.a-_t87bab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.04 5.51l-.8-3m10.72 40l.8 2.98M42.5 19.05l3-.81m-40 10.72l-3 .81");
}

:global(.kzbvcpbzi) {
  cx: 24px;
  cy: 24.01px;
  r: 19.15px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
