<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><circle class="hj49tupui"/><circle class="bu9ai6b5q"/><circle class="ygzs89baa"/><circle class="dn64-9b5z"/><circle class="lhdrfib_g"/><circle class="mww6wk8hk"/><path class="ifyph1aqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flushed-face" {...props}></Icon>
<style>
:global(.bu9ai6b5q) {
  cx: 7px;
  cy: 23px;
  r: 5px;
  fill: var(--svg-color--ff7892, #ff7892);
}

:global(.dn64-9b5z) {
  cx: 11.5px;
  cy: 16.5px;
  r: 5.5px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

:global(.hj49tupui) {
  cx: 29px;
  cy: 23px;
  r: 5px;
  fill: var(--svg-color--ff7892, #ff7892);
}

:global(.ifyph1aqj) {
  fill: var(--svg-color--664500, #664500);
  d: path("M22 30h-8a1 1 0 1 1 0-2h8a1 1 0 1 1 0 2m8.001-19a1 1 0 0 1-.801-.4c-2.64-3.521-6.061-3.598-6.206-3.6a1 1 0 0 1-.991-1.005A.997.997 0 0 1 23 5c.184 0 4.537.05 7.8 4.4a1 1 0 0 1-.799 1.6M5.999 11A1 1 0 0 1 5.2 9.4C8.462 5.05 12.816 5 13 5a1 1 0 0 1 .004 2c-.155.002-3.568.086-6.204 3.6a1 1 0 0 1-.801.4");
}

:global(.lhdrfib_g) {
  cx: 11.5px;
  cy: 16.5px;
  r: 2.5px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.mww6wk8hk) {
  cx: 24.5px;
  cy: 16.5px;
  r: 2.5px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.tg31urbgg) {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

:global(.ygzs89baa) {
  cx: 24.5px;
  cy: 16.5px;
  r: 5.5px;
  fill: var(--svg-color--f5f8fa, #f5f8fa);
}

</style>
