<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="uih2s6b6k"/><path class="kdr-xzbfv"/><path class="jrsksb7rz"/><path class="awy6a3qja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-flag-st-lucia" {...props}></Icon>
<style>
:global(.awy6a3qja) {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M32 33L20 45h24z");
}

:global(.jrsksb7rz) {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 21L20 45h24z");
}

:global(.kdr-xzbfv) {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 15L17 45h30z");
}

:global(.uih2s6b6k) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--49c3f2, #49c3f2);
}

</style>
