<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="w-andb8bx"/><path class="c-bazabch"/><path class="py37u_7id"/><circle class="tieb_sdfa"/><circle class="d_utawb_a"/><circle class="rh0m0lm3b"/><circle class="ixznsmb0n"/><path class="w0jew3buq"/><path class="vjf51jb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:police-car" {...props}></Icon>
<style>
:global(.c-bazabch) {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M1 26v2c0 .09.021.175.026.263A1.99 1.99 0 0 0 0 30a2 2 0 0 0 2 2h30a4 4 0 0 0 4-4v-2c0-.348-.059-.679-.142-1H1.201A2.8 2.8 0 0 0 1 26");
}

:global(.d_utawb_a) {
  cx: 10px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

:global(.ixznsmb0n) {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

:global(.py37u_7id) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M15.91 32c.055-.326.09-.658.09-1a6 6 0 0 0-12 0c0 .342.035.674.09 1zm17 0c.055-.326.09-.658.09-1a6 6 0 0 0-12 0c0 .342.035.674.09 1z");
}

:global(.rh0m0lm3b) {
  cx: 27px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.tieb_sdfa) {
  cx: 10px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.vjf51jb0c) {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M22 13a1 1 0 0 1-1 1h-2a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1m1 8h7s-2-5-3-5h-4zm-2-5h-5c-2 0-5 5-5 5h10z");
}

:global(.w-andb8bx) {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M32 22s-2-8-5-8H16c-3 0-7 7-7 7s-8 1-8 5v2c0 .09.021.175.026.263A1.99 1.99 0 0 0 0 30a2 2 0 0 0 2 2h30a4 4 0 0 0 4-4v-2a4 4 0 0 0-4-4");
}

:global(.w0jew3buq) {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M21 13a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h3a1 1 0 0 1 1 1");
}

</style>
