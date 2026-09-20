<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ni20md-jo"/><path class="j6o0shbiv"/><path class="uesvxd39h"/><path class="hh0-34bql"/><path class="y5y9-x5ge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-rate-limit-outline-regular" {...props}></Icon>
<style>
:global(.hh0-34bql) {
  d: path("m9 8 3 3 3 -3");
}

:global(.j6o0shbiv) {
  d: path("M7 18h5");
}

:global(.ni20md-jo) {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uesvxd39h) {
  d: path("M15 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y5y9-x5ge) {
  d: path("M12 11v3");
}

</style>
