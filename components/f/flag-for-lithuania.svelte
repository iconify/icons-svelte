<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="do6g26bwg"/><path class="r3m9_5yhm"/><path class="sqy512b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-lithuania" {...props}></Icon>
<style>
:global(.do6g26bwg) {
  fill: var(--svg-color--006a44, #006a44);
  d: path("M0 14h36v8H0z");
}

:global(.r3m9_5yhm) {
  fill: var(--svg-color--fdb913, #fdb913);
  d: path("M32 5H4a4 4 0 0 0-4 4v5h36V9a4 4 0 0 0-4-4");
}

:global(.sqy512b9q) {
  fill: var(--svg-color--c1272d, #c1272d);
  d: path("M4 31h28a4 4 0 0 0 4-4v-5H0v5a4 4 0 0 0 4 4");
}

</style>
