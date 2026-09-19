<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="d2krg-08m"/><path class="q1zpp1cfx"/><path class="x6rw_x3-x"/><circle class="vmntolbhe"/><circle class="u-heik6bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-taiwan" {...props}></Icon>
<style>
:global(.d2krg-08m) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2v30H2c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2");
}

:global(.q1zpp1cfx) {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C15.4 2 2 15.4 2 32h30z");
}

:global(.u-heik6bk) {
  cx: 19px;
  cy: 19px;
  r: 5px;
  fill: var(--svg-color--fff, #fff);
}

:global(.vmntolbhe) {
  cx: 19px;
  cy: 19px;
  r: 5.7px;
  fill: var(--svg-color--428bc1, #428bc1);
}

:global(.x6rw_x3-x) {
  fill: var(--svg-color--fff, #fff);
  d: path("m24 20.3l5-1.3l-5-1.3l3.7-3.7l-5 1.3l1.3-5l-3.7 3.7L19 9l-1.3 5l-3.7-3.7l1.3 5l-5-1.3l3.7 3.7L9 19l5 1.3l-3.7 3.7l5-1.3l-1.3 5l3.7-3.7l1.3 5l1.3-5l3.7 3.7l-1.3-5l5 1.3z");
}

</style>
