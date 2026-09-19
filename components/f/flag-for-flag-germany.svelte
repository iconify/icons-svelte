<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zsvz6xdlk"/><path class="x2c4yqsoh"/><path class="dmuqxvx3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:flag-for-flag-germany" {...props}></Icon>
<style>
:global(.dmuqxvx3l) {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

:global(.x2c4yqsoh) {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

:global(.zsvz6xdlk) {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 25h64v14H0z");
}

</style>
