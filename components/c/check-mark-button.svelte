<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="kfs7nwd-w"/><path class="xgrwu_xlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:check-mark-button" {...props}></Icon>
<style>
:global(.kfs7nwd-w) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4bd37b, #4bd37b);
}

:global(.xgrwu_xlq) {
  fill: var(--svg-color--fff, #fff);
  d: path("M46 14L25 35.6l-7-7.2l-7 7.2L25 50l28-28.8z");
}

</style>
