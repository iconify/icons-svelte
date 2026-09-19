<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zzyf9-41q"/><path class="mfs7-u_9i"/><path class="qo6etfbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:flag-for-cote-divoire" {...props}></Icon>
<style>
:global(.mfs7-u_9i) {
  fill: var(--svg-color--f7941e, #f7941e);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

:global(.qo6etfbxu) {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M54 10H42v44h12c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

:global(.zzyf9-41q) {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M22 10h20v44H22z");
}

</style>
