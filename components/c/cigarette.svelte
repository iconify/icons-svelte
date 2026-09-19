<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="aim3b90ep"/><path class="ebon3_bsc"/><path class="mnd1yj6-n"/><path class="vyn3247hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:cigarette" {...props}></Icon>
<style>
:global(.aim3b90ep) {
  fill: var(--svg-color--f2b200, #f2b200);
  d: path("M0 50h26v14H0z");
}

:global(.ebon3_bsc) {
  fill: var(--svg-color--dce5e5, #dce5e5);
  d: path("M26 50h34v14H26z");
}

:global(.mnd1yj6-n) {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M60 50h4v14h-4z");
}

:global(.vyn3247hv) {
  fill: var(--svg-color--abc2c6, #abc2c6);
  d: path("M33.5 16C28.4 35.1 43.9 9 64 47C53.3 32.9 18.8 43.2 4.3 27.5C-15.8 5.8 41.9-15.6 33.5 16");
}

</style>
