<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="qm7pesb5s"/><path class="e5xzwot2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:no-entry" {...props}></Icon>
<style>
:global(.e5xzwot2c) {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 26h46v12H9z");
}

:global(.qm7pesb5s) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ff5a79, #ff5a79);
}

</style>
