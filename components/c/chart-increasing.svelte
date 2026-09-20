<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t8v0an0fk"/><path class="omgfyk3rt"/><path class="l34g7mbip"/><path class="c4noegs4p"/><path class="r9wo5nbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto:chart-increasing" {...props}></Icon>
<style>
:global(.c4noegs4p) {
  fill: var(--svg-color--e53935, #e53935);
  d: path("m5.1 122.98l-.08-6.16L31.94 68.3l23.7 21.91l63.78-85.1h3.49l.14 5.16l-66.6 88.86l-23.02-21.28l-24.98 45.16z");
}

:global(.l34g7mbip) {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M123.8 24.66H4.15m119.66 19.67H4.16M123.83 64H4.17m119.67 19.67H4.19m119.66 19.67H4.2");
}

:global(.omgfyk3rt) {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-993px, 1.993px);
  d: path("M24.7 4.2v119.6M44.35 4.2v119.6M64 4.2v119.6M83.65 4.2v119.6M103.3 4.2v119.6");
}

:global(.r9wo5nbmc) {
  fill: var(--svg-color--b0bec5, #b0bec5);
  d: path("M122.01 5.99V122H5.99V5.99zM124 4H4v120h120z");
}

:global(.t8v0an0fk) {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 4h120v120H4z");
}

</style>
