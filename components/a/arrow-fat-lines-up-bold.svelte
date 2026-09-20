<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rzt747w1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-fat-lines-up-bold" {...props}></Icon>
<style>
:global(.rzt747w1f) {
  fill: currentColor;
  d: path("m232.49 111.51l-96-96a12 12 0 0 0-17 0l-96 96A12 12 0 0 0 32 132h36v4a12 12 0 0 0 12 12h96a12 12 0 0 0 12-12v-4h36a12 12 0 0 0 8.49-20.49M176 108a12 12 0 0 0-12 12v4H92v-4a12 12 0 0 0-12-12H61l67-67l67 67Zm12 108a12 12 0 0 1-12 12H80a12 12 0 0 1 0-24h96a12 12 0 0 1 12 12m0-40a12 12 0 0 1-12 12H80a12 12 0 0 1 0-24h96a12 12 0 0 1 12 12");
}

</style>
