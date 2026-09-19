<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="dy9u4yopw"/><circle class="zne7fwbye"/><circle class="rl0d2sb8f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:face-with-open-mouth" {...props}></Icon>
<style>
:global(.dy9u4yopw) {
  cx: 32px;
  cy: 45.1px;
  r: 7px;
}

:global(.fbp0m0b1e) {
  fill: var(--svg-color--664e27, #664e27);
}

:global(.rhvdvboaq) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

:global(.rl0d2sb8f) {
  cx: 42.7px;
  cy: 25px;
  r: 4.5px;
}

:global(.zne7fwbye) {
  cx: 20.2px;
  cy: 25px;
  r: 4.5px;
}

</style>
