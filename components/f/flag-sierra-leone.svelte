<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="zut58gbmm"/><path class="f-uxkkfru"/><path class="k-mxk9bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-sierra-leone" {...props}></Icon>
<style>
:global(.f-uxkkfru) {
  fill: var(--svg-color--1eb53a, #1eb53a);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

:global(.k-mxk9bag) {
  fill: var(--svg-color--0072c6, #0072c6);
  d: path("M4 31h28a4 4 0 0 0 4-4v-5H0v5a4 4 0 0 0 4 4");
}

:global(.zut58gbmm) {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 14h36v8H0z");
}

</style>
