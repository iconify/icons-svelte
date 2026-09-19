<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jsdx1e7ly"/><g class="hq2-vcghy"><path class="qqht6ibhg"/><path class="le-7_3ngl"/><path class="ngbb5qbmi"/><path class="r1h1uuyoy"/><path class="lqcv_wb6m"/><path class="inbx0r06w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-georgia" {...props}></Icon>
<style>
:global(.hq2-vcghy) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

:global(.inbx0r06w) {
  d: path("M42 52v-4l6 1l6-1v4l-6-1z");
}

:global(.jsdx1e7ly) {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M38 2.6H26C14.3 5 5 14.2 2.6 26v12C5 49.8 14.3 59 26 61.4h12C49.8 59 59 49.7 61.4 38V26C59 14.2 49.7 5 38 2.6");
}

:global(.le-7_3ngl) {
  d: path("M18 20h-4l1-6l-1-6h4l-1 6z");
}

:global(.lqcv_wb6m) {
  d: path("M10 52v-4l6 1l6-1v4l-6-1zm40 4h-4l1-6l-1-6h4l-1 6z");
}

:global(.ngbb5qbmi) {
  d: path("M10 16v-4l6 1l6-1v4l-6-1zm40 4h-4l1-6l-1-6h4l-1 6z");
}

:global(.qqht6ibhg) {
  d: path("M38 26V2.6Q35.15 2 32 2c-3.15 0-4.1.2-6 .6V26H2.6Q2 28.85 2 32c0 3.15.2 4.1.6 6H26v23.4q2.85.6 6 .6c3.15 0 4.1-.2 6-.6V38h23.4q.6-2.85.6-6c0-3.15-.2-4.1-.6-6z");
}

:global(.r1h1uuyoy) {
  d: path("M42 16v-4l6 1l6-1v4l-6-1zM18 56h-4s1-4.5 1-6s-1-6-1-6h4s-1 4.5-1 6s1 6 1 6");
}

</style>
