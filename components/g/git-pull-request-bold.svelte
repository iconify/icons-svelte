<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w4cg07b1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:git-pull-request-bold" {...props}></Icon>
<style>
:global(.w4cg07b1n) {
  fill: currentColor;
  d: path("M108 64a36 36 0 1 0-48 33.94v60.12a36 36 0 1 0 24 0V97.94A36.07 36.07 0 0 0 108 64M72 52a12 12 0 1 1-12 12a12 12 0 0 1 12-12m0 152a12 12 0 1 1 12-12a12 12 0 0 1-12 12m140-45.94v-47.43a27.8 27.8 0 0 0-8.2-19.8L173 60h19a12 12 0 0 0 0-24h-48a12 12 0 0 0-12 12v48a12 12 0 0 0 24 0V77l30.83 30.83a4 4 0 0 1 1.17 2.83v47.43a36 36 0 1 0 24 0ZM200 204a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
