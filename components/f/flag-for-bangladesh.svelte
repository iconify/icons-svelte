<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="uhgwdubil"/><circle class="qja0zjb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:flag-for-bangladesh" {...props}></Icon>
<style>
:global(.qja0zjb8u) {
  fill: var(--svg-color--f42a41, #F42A41);
  cx: 16px;
  cy: 17.5px;
  r: 7px;
}

:global(.uhgwdubil) {
  fill: var(--svg-color--006a4d, #006A4D);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

</style>
