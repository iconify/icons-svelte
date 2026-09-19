<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hiqb3w74p"/><path class="z2lnkgbvd"/><path class="wu6yuabua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:flag-for-russia" {...props}></Icon>
<style>
:global(.hiqb3w74p) {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M31.9 2c-13 0-24.1 8.4-28.2 20h56.6C56.1 10.4 45 2 31.9 2");
}

:global(.wu6yuabua) {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M3.7 22C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

:global(.z2lnkgbvd) {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M31.9 62c13.1 0 24.2-8.4 28.3-20H3.7c4.1 11.7 15.2 20 28.2 20");
}

</style>
