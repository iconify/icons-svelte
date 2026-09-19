<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="do2tny6mn"/><circle class="koquvbcvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-flag-japan" {...props}></Icon>
<style>
:global(.do2tny6mn) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

:global(.koquvbcvx) {
  cx: 32px;
  cy: 32px;
  r: 12px;
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

</style>
