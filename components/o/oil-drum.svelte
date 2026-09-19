<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="c4lhfmbbh"/><ellipse class="i3_8-dbcw"/><ellipse class="hqxdi0bsg"/><ellipse class="apcq127ff"/></g><g class="j9357eg9x"><ellipse class="ot0qi0bck"/><path class="yp5rutbzd"/></g><ellipse class="s6smfub7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:oil-drum" {...props}></Icon>
<style>
:global(.apcq127ff) {
  cx: 32px;
  cy: 40.4px;
  rx: 26px;
  ry: 4.9px;
}

:global(.c4lhfmbbh) {
  d: path("M7.1 6.9h49.8v50.2H7.1z");
}

:global(.hqxdi0bsg) {
  cx: 32px;
  cy: 23.6px;
  rx: 26px;
  ry: 4.9px;
}

:global(.i3_8-dbcw) {
  cx: 32px;
  cy: 57.1px;
  rx: 26px;
  ry: 4.9px;
}

:global(.j9357eg9x) {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

:global(.jeunsn1yj) {
  fill: var(--svg-color--3e4347, #3e4347);
}

:global(.ot0qi0bck) {
  cx: 32px;
  cy: 6.9px;
  rx: 26px;
  ry: 4.9px;
}

:global(.s6smfub7f) {
  cx: 15.7px;
  cy: 6.9px;
  fill: var(--svg-color--3e4347, #3e4347);
  rx: 3.9px;
  ry: 1px;
}

:global(.yp5rutbzd) {
  d: path("M7.4 22.4c3.5 1.9 13.2 4.2 24.6 4.2s21.1-2.3 24.6-4.2c-6.2.9-14.9 2.4-24.6 2.4s-18.4-1.4-24.6-2.4m0 16.9c3.5 1.9 13.2 4.2 24.6 4.2s21.1-2.3 24.6-4.2c-6.2.9-14.9 2.4-24.6 2.4s-18.4-1.5-24.6-2.4m0 16.3c3.5 1.9 13.2 4.2 24.6 4.2s21.1-2.3 24.6-4.2c-6.2.9-15 2.4-24.6 2.4s-18.4-1.5-24.6-2.4");
}

</style>
